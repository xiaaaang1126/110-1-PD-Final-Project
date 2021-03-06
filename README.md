# 110-1-PD-Final-Project

## function of **_mapGenerator.cpp_**
- restore the map data in a two-dimensional 9x9 integer array
- the original map (ie. solution) is named _**map**_, and the unbalanced map is named **_puzzle_**
- the empty entries are represented as 0
- please apply the solution-finding algorithm on **_puzzle_**
- if the **_puzzle_** is illegal (that means the puzzle has multiple solutions or no solutions), please use **_gen_puzzle()_** to generate another puzzle

---
## Project Outline
- Back-End
  - Map Generator: 
    1. generate a full sudoku-map
  - Map Deleter: 
    1. dig different numbers of hole according to different stage of difficulty
    2. make sure the unbalanced sudoku-map has unique solution
  - Sudoku Solver: 
    1. given a unbalanced sudoku map, find the unique solution
    2. (*optional) record each step of filling empty entry for displaying if needed [(refer.)](https://www.gushiciku.cn/pl/glKd/zh-tw)
- Front-End
  - Graphical User Interface: users are available to operate with these function:
    1. clcik to start the game and see the unbalanced sudoku-map
    2. assign the number in the empty block on sudoku-map
    3. click to check whether his answer is correct or not
