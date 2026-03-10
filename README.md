# KidsGamifyCodingTest 🎮

An interactive, gamified learning platform designed to make coding fun for kids! This application combines engaging gameplay with educational content, complete with sound effects, scoring systems, and multiple difficulty levels.

## Features ✨

- **Gamified Learning**: Interactive quiz-style gameplay with scoring and performance tracking
- **Multiple Levels**: Progression through different difficulty levels
- **Audio Feedback**: Sound effects for correct answers, wrong answers, and background music
- **Progress Tracking**: Real-time display of:
  - Score
  - Attempts
  - Questions answered
  - Performance percentage
- **Music Controls**: Toggle background music on/off
- **Kid-Friendly Interface**: Simple, intuitive button-based navigation

## Project Structure 📁

```
KidsGamifyCodingTest/
├── html/                   # Game pages
│   ├── index.html         # Level 1 game interface
│   └── level_two.html     # Level 2 game interface
├── css/                    # Styling
│   ├── index.css          # Level 1 styles
│   └── leveltwo.css       # Level 2 styles
├── jscontrollers/         # Game logic
│   ├── main.js            # Main game controller
│   ├── index.js           # Level 1 controller
│   ├── level_two.js       # Level 2 controller
│   └── questions.js       # Question data and logic
├── resources/             # Media assets
│   ├── audio/             # Sound effects and background music
│   └── images/            # Game graphics and icons
└── package.json           # Project configuration
```

## Getting Started 🚀

### Prerequisites
- Node.js (v12 or higher)
- Electron (for running the desktop application)

### Installation

1. **Clone or download the project**
   ```bash
   cd KidsGamifyCodingTest
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the application**
   ```bash
   npm start
   ```
   (Or if using Electron: `electron .`)

## How to Play 🎯

1. **Start Screen**: Click the **START** button to begin
2. **Answer Questions**: Read each question and click the correct answer
3. **Track Progress**: Monitor your:
   - Score (points earned)
   - Attempts (number of tries)
   - Questions answered (progress out of total)
   - Performance (percentage correct)
4. **Audio Control**: Use the checkbox in the top-left to toggle background music
5. **Quit**: Click **QUIT** to exit the game

## Levels 📚

### Level 1 (index.html)
- Entry-level questions
- Ideal for beginners
- Foundation concepts

### Level 2 (level_two.html)
- Advanced questions
- For experienced players
- More challenging content

## Game Controls 🎮

| Control | Action |
|---------|--------|
| **START** | Begin the game |
| **QUIT** | Exit the game |
| **Music Toggle** | Enable/disable background music |
| **Answer Buttons** | Select your answer |

## Audio Files 🔊

The game includes various sound effects for enhanced gameplay:
- `audio3.mp3` - Background music
- `pop1.mp3` - UI button hover sound
- `play.mp3` - Game start sound
- `coins.mp3` - Success/reward sound
- `correctnext.mp3` - Correct answer sound
- `alertWrong.mp3` - Wrong answer sound

## Customization 🛠️

### Adding Questions
Edit `jscontrollers/questions.js` to add or modify questions for each level.

### Styling Changes
- Update `css/index.css` for Level 1 appearance
- Update `css/leveltwo.css` for Level 2 appearance

### Audio Changes
Replace audio files in `resources/audio/` with your own sound effects.

## Technical Stack 💻

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Desktop**: Electron
- **Database**: SQLite3
- **Package Manager**: NPM

## Troubleshooting ❓

| Issue | Solution |
|-------|----------|
| Audio not playing | Check browser/Electron audio permissions |
| Styles not loading | Ensure CSS file paths are correct |
| Game not starting | Verify all JS files are in `jscontrollers/` folder |

**Enjoy learning and gaming!** 🎉
