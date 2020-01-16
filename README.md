# emoji-minesweeper [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

### How to play

- Left click to step on a spot
- Right click to mark a spot as a bomb
- Double click to open all 8 spots nearby a target (except ones already marked as bombs using right clicks)


### API

```javascript
// to start a new game
new Game(cols, rows, bombs, [emptyemoji, bombemoji, flagemoji, starteremoji], twemojiOrNot)

// for example:
new Game(10, 10, 10, ["🌱", "💥", "🚩", "◻️"], true)
new Game(16, 16, 30, ["🐱", "📛", "💣", "🔍"], false)
```

### Todos

- Mobile!

### Zap :zap:

:heart: https://github.com/twitter/twemoji

### Why

[WHY IS THIS A QUESTION?!](https://twitter.com/muanchiou/status/601633821012856832)
