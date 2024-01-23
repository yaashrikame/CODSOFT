get_user_choice(): This function prompts the user to enter their choice and validates it. 
It ensures that the user enters a valid choice (rock, paper, or scissors) and converts it to lowercase for consistency.

get_computer_choice(): This function generates a random choice for the computer using the random.choice() function. 
It selects one of the options: rock, paper, or scissors.

determine_winner(user, computer): This function takes the user's choice and the computer's choice as arguments 
and determines the winner based on the rules mentioned earlier.
It returns a string indicating the result (tie, user win, or computer win).

play_game(): This function is the main game loop. 
It initializes the user's and computer's scores to 0 and repeatedly prompts the user for their choice,
generates the computer's choice, determines the winner, updates the scores, and asks if the user wants to play again.
