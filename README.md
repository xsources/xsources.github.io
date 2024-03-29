
Python simulation of site percolation on square lattice:
Two python applications are presented here to simulate the percolation process on the square lattice. The first, more flexible uses Django application while the second is developed with the help of python Jupyter framework.

1. Percolation with django app: (variable size with a square side varying between 10 and 1000)
   https://pythonyx.pythonanywhere.com/percolation/

2. Percolation developed with Jupyter framework, (100x100) square lattice system. This application computes and updates at each click on the "Next" button the following elements:
- the probability (p)
- the concentration (c) of "occupied sites"
- the size of the lagest component (LC), colored in red
At the percolation threshold pc=0.5927, the largest component spans the percolation system by joining two opposite sides of the square grid.

On the right side of the app, the percolation function θ(p) (the probability for a site to belong to the largest component) is plotted dot by dot, at each button click. 
The Python code source is displayed.

https://xsources.github.io/sitepercol.html

The phase transition is obseved near the percolation threshold at pc=0.593 in the  θ(p) function.
