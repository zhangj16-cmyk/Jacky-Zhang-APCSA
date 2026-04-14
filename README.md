Sudoku Generator - by Jacky Zhang

This is a java console program that generates and displays a fully random, valid 9 by 9 Sudoku puzzle every time it is run.


**How To Run This Program**

1. Copy/Download the Code
2. Open a terminal/command prompt
3. Paste code & run

This Sudoku board is generated using a structured randomization process. First, the cyclic shift formula creates a 9 by 9 grid where each row column and 3 by 3 box contains the digits 1-9 once. The digits are then randomized through shuffling a arraylist of the numbers 1-9 and remapping each value. After, rows within each group of 3 are shuffled, followed by shuffling columns within each group of 3, ensuring the board stays valid while appearing random.
