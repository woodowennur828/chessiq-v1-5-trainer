# ChessIQ v1.5 - positional chess training tool 2026

> **ChessIQ is a browser-based trainer for positional chess. Version 1.5 helps players develop evaluation, strategic planning, and practical decision-making skills using positions from real games.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.5-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/woodowennur828/chessiq-v1-5-trainer?style=flat-square)](https://github.com/woodowennur828/chessiq-v1-5-trainer)

---

<p align="center">
  <a href="https://woodowennur828.github.io/chessiq-v1-5-trainer/">
    <img src="https://img.shields.io/badge/Download-ChessIQ%20Latest-brightgreen?style=for-the-badge" alt="Download ChessIQ">
  </a>
</p>

> **[Download ChessIQ v1.5](https://woodowennur828.github.io/chessiq-v1-5-trainer/)**

---

[Download Latest Build](https://woodowennur828.github.io/chessiq-v1-5-trainer/)

---

## What ChessIQ Does

ChessIQ targets a part of chess improvement that goes beyond recognizing tactical motifs: understanding the character of a position. The trainer uses real positions sourced from Lichess to help players assess exchanges, compare strategic plans, and decide whether the advantage belongs to White, Black, or neither side.

The application runs on the web through HTML and JavaScript. Firebase provides account and leaderboard functionality, allowing ChessIQ to support independent study, structured training sessions, and repeated practice with progress tracking.

---

## Core Capabilities

- Strategic puzzle sessions centered on positional evaluation
- Real-game training positions sourced from Lichess
- Evaluation exercises for White, Black, or an equal position
- Engine feedback to help review each answer
- Multiple difficulty settings for varying levels of practice
- User accounts and leaderboards for recording progress
- Analytics for following improvement across sessions
- Web-focused design, with mobile support planned

---

## Getting Started

Download the project files or clone the repository, then launch the web application in a browser.

1. Clone the source repository:
   - `git clone https://github.com/woodowennur828/chessiq-v1-5-trainer.git
2. Move into the project directory:
   - `cd chessiq-positional-training`
3. Open the HTML entry point in your preferred web environment or serve it locally.
4. When using a local server, start that server before opening the app so browser functionality and Firebase access can operate correctly.

---

## Using the Trainer

1. Launch ChessIQ in a modern browser.
2. Select a difficulty level or training route.
3. Examine the displayed position and choose your evaluation.
4. Read the engine feedback once the attempt is complete.
5. Review account statistics and leaderboard results when those features are enabled.

A normal practice session can include:

- Solving positions taken from real games
- Comparing your judgment with the expected evaluation
- Repeating exercises to reinforce positional ideas
- Reviewing analytics to identify consistent strengths and weaknesses

---

## Settings and Firebase Configuration

ChessIQ configuration is managed through the web application and its Firebase connection.

Relevant settings may cover:

- Account and leaderboard configuration
- Selection of training modes
- Preferences for progress tracking
- Firebase connection values required by the application

A representative configuration structure is:

    {
      "firebase": {
        "projectId": "your-project-id",
        "apiKey": "your-api-key"
      },
      "training": {
        "difficulty": "medium",
        "mode": "positional"
      }
    }

When no configuration screen is available, inspect the application source and the Firebase project settings to locate the values used by the app.

---

## System Requirements

- A current web browser
- Browser support for HTML and JavaScript
- Firebase access for account and leaderboard functionality
- Internet connectivity when retrieving online game data or other remote services
- Enough browser storage for cache contents and saved session information

---

## Common Questions

**How can I install the newest version?**  
Follow the download link above, or review the repository for the latest build and source updates.

**Where can I find the application settings?**  
The web app handles most settings. Firebase stores the account-related and leaderboard data used by the project.

**What should I do if a position fails to load?**  
Reload the page, check that your browser is supported, and make sure the necessary online services are available.

**Are different difficulty levels available?**  
Yes. The training flow includes selectable difficulty modes.

**Does ChessIQ work on mobile devices?**  
Mobile support is planned. Until then, results may differ depending on the device and browser.

---

## License

ChessIQ is released under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
