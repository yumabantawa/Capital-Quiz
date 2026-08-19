# Capital Quiz Game

A simple command-line quiz game that tests your knowledge of world capitals. The game picks a random country, asks you for its capital, and keeps score as you go.

## Features

- Covers 190+ countries and their capitals
- Randomly selects a new country after every answer
- Tracks your running score
- Shows your final accuracy percentage when you quit

## Requirements

- Python 3.x (no external dependencies — uses only the built-in `random` module)

## How to Run

```bash
python capital_quiz.py
```

## How to Play

1. When prompted, type the capital city of the country shown.
2. If you're correct, your score goes up and you'll see a new country.
3. If you're incorrect, you'll see a new country (no penalty, just no point).
4. Type `exit` at any time to quit and see your final score and accuracy.

**Example:**
```
What is the capital of France: Paris
Correct! Your score is 1
What is the capital of Japan: Tokyo
Correct! Your score is 2
What is the capital of Egypt: exit
Thank you for playing.
Your final score is 2
You have successfully answered 100.0% of the questions.
```

## Project Structure

```
.
├── capital_quiz.py   # main game script
├── README.md
└── .gitignore
```


