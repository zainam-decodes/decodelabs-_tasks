# Password Strength Checker
### Cybersecurity Internship — Project 1

A browser-based password strength evaluator built with vanilla HTML, CSS, and JavaScript.

## Features
- Real-time password evaluation (Weak / Medium / Strong)
- Entropy calculation using `length × log₂(pool_size)`
- Checks for: length, uppercase, lowercase, numbers, symbols, repeated characters
- Common/leaked password detection (40+ entries)
- Actionable improvement suggestions
- Show/hide password toggle
- Light + dark mode support

## How to Run
Just open `index.html` in any browser — no server, no dependencies, no build step.

## Scoring Logic
| Score | Result |
|-------|--------|
| 0–3   | Weak   |
| 4–6   | Medium |
| 7–8   | Strong |

Points awarded for: length ≥ 8, length ≥ 12, uppercase, lowercase, number, symbol, no repeated chars, entropy ≥ 60 bits. Common passwords are hard-capped at Weak.

## Files
- `index.html` — complete single-file application
- `README.md`  — this file
VIEW THE SITE -https://zainam-decodes.github.io/decodelabs-_tasks/
