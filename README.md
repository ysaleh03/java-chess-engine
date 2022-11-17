# Chess
## Chess Engine

This application is a chess game, where users have the
option to play against one another. It can be used by 
anyone who wants to play a game of chess, and could also
be used by chess strategists to come up with or test new strategies.

Some additional functionalities include:
- saving the current board
- loading a previously saved board
- a leaderboard

This project is interesting because it needs to deal with a 
large variety of user interactions and check them against the 
movesets of different pieces.

## User Stories:
1. As a user, I want to be able to play vs another user (done)
2. As a user, I want to set up a board with pieces on it (done)
3. As a user, I want to select pieces and move them (done)
    * No special moves, unfortunately (sorry)
4. As a user, I want to capture pieces on the board (done)
5. As a user, I want to add captured pieces to the player's captures list (done)
6. As a user, I want to see the pieces I captured (done)
7. As a user, I want to know how many turns my game ended in (done)
8. As a user, I want to save my game for later (done)
9. As a user, I want to load a game from earlier (done)
10. As a user, I want to add my name to the leaderboard (done)

## Instructions for Grader
1. Select "Load Game"
2. Select "FooBarTurn0.json"

3. As player1, select the white pawn at c2 by clicking on it
4. As player1, move the selected piece two squares forward by clicking on c4
5. As player2, select the black pawn at d7 by clicking on it
6. As player2, move the selected piece two squares forward by clicking on d5
7. As player1, move the white pawn now at c4 to d5, taking the black pawn there
8. Similarly, as player2, take that pawn with the black queen
   * The taken pawns should appear at the bottom of the frame as they are taken

9. Keep playing until you win, or close the frame
10. A small dialogue box should pop up, prompting you to save. Click "Yes".
11. Choose a name for the save, then click "Save"