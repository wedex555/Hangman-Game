# Hangman-Game
Hangman game in JavaScript

This is the classic Hangman game where the player is given a word and has 5 chances to guess the word one letter at a time.

Game Interface
Blank spaces are displayed on the screen equal to the length of the word chosen randomly from a list. Player can guess a letter by pressing a keyboard key. If the letter is present in the word, the blank spaces are replaced with the letter at the right position. If the letter occurs more than once in the word, each occurence of the letter is replaced for a correct guess.

A letter can be guessed only once and for each wrong guess, the chances are decreased by 1 and hangman image is drawn on the canvas part by part till all the five chances are used up.

A new word is chosen after a successful game or after 5 guesses are up. 

## Live demo
https://wedex555.github.io/Hangman-Game/.

## Description
- Simply begin typing to enter your guesses
<img width="1415" alt="Screen Shot 2019-05-26 at 10 32 51 AM" src="https://user-images.githubusercontent.com/46644726/58385238-02357c80-7fa2-11e9-9e82-94cc4a0ddb98.png">

- You only have 5 guesses until the current word is cleared and the next one is loaded
<img width="1413" alt="Screen Shot 2019-05-26 at 10 33 38 AM" src="https://user-images.githubusercontent.com/46644726/58385249-301ac100-7fa2-11e9-928c-725c28880b47.png">

- Your wins and failed attempts are recorded

## Requirements
1. Create a hangman game that inputs key presses from the user
2. Track guesses and number of wins
3. Win result in an increase in the win count and both wins and losses result in the loading of a new word

## Technologies Used
- HTML/CSS
- JavaScript for DOM manipulation
- Web Fonts (from Google Fonts)
- TypeIt for visual effect
- jQuery for visual effect and TypeIt requires it

## Code Explaination
- Basically, the meat and potatoes of the code is in the JavaScript file (game.js), where the variables and game logic is stored
- The HTML sets up the basic elements of the game such as the title, pictures and audio, text elements indicating progress and points, etc.
- The CSS is really the visual aspect of this project, giving the colors and margins, etc. Flexbox was of enormous use in the project (particularly in customizing the scaling of elements)
- External web fonts, audio, and visual effects were added to spice things up


