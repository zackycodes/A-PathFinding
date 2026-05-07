# A* Pathfinding Maze Visualizer
A Python-based GUI application that generates a solvable random maze and visualizes a snake navigating from start to finish using the A Search Algorithm*.

## 🚀 Features
* __Procedural Maze Generation__: Creates a new grid on every run with random obstacles.
* __Solvability Guarantee__: Re-generates the maze until a valid path exists between the start and end points.
* __A*Pathfinding__: Utilizes a priority queue (heap) and Manhattan distance heuristic to calculate the most efficient route.
* __Real-time Animation__: Visualizes the path execution step-by-step using a Tkinter-based interface.

## 🛠️ Requirements
* Python 3.x
* numpy (for grid manipulation)
* tkinter (standard Python GUI library)

## 📖 How to Use
Install dependencies:
`pip install numpy`

Run the script:
`python Astarpath.py`

- Green Square: Starting Point (0, 0).
- Red Square: Target Food ((GRID_SIZE-1, GRID_SIZE-1)).
- Blue Trail: The path currently being traversed.

## ⚙️ Configuration
You can adjust the following constants at the top of the file to change the simulation behavior:

* GRID_SIZE: Change the number of cells in the maze (default: 20).
* SNAKE_SPEED: Adjust the delay (in ms) between movements (default: 100).
* WIDTH/HEIGHT: Modify the window resolution (default: 600x600).

## Notes
Enjoy!
