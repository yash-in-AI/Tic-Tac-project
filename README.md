# Tic-Tac-Toe AI Bots

A clean and professional Tic-Tac-Toe repository that includes:

- Human vs Human gameplay.
- Human vs AI gameplay using the Minimax algorithm.
- Pre-trained state-value files for reinforcement-learning experiments.

## Project Overview

This repository demonstrates different ways to implement Tic-Tac-Toe in Python. It is designed for learning and experimentation with game-playing algorithms, particularly the Minimax strategy for unbeatable AI moves.

## Included Files

- `HumanvsAI_Minimax.py` — Play against a Minimax-based AI opponent.
- `HumanvsHuman.py` — Two-player Tic-Tac-Toe for human vs human matches.
- `trained_state_values_O.txt` — Saved state values for the O player from reinforcement-learning experiments.
- `trained_state_values_X.txt` — Saved state values for the X player from reinforcement-learning experiments.
- `FUNDING.yml` — GitHub funding metadata.

## Features

- Console-based Tic-Tac-Toe gameplay.
- AI opponent using Minimax decision making.
- Easy-to-use interface with numbered board positions.
- Reusable game logic for further algorithm experiments.

## How to Run

Make sure Python is installed, then run one of the following commands from the project folder.

### Play against the Minimax AI

```bash
python HumanvsAI_Minimax.py
```

### Play against another human player

```bash
python HumanvsHuman.py
```

## Gameplay Notes

- The board positions are entered as numbers 1 through 9.
- In `HumanvsAI_Minimax.py`, the AI plays optimally using the Minimax algorithm.
- In `HumanvsHuman.py`, two human players alternate turns until a win or draw occurs.

## Recommended Improvements

- Add a dedicated Reinforcement Learning training script.
- Create a graphical user interface (GUI).
- Add unit tests for game logic and state validation.

## License

This project is provided for learning and experimentation. Feel free to adapt it for your own GitHub portfolio.

