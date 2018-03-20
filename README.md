# Why DBSCAN?

The task was to cluster the 3d dataset with **non-hierarchical** clustering algorithm. The number of clusters is **dynamical**.

For this task I used DBSCAN. DBSCAN is a pretty *fast* algorithm for clustering. It has complexity of *O(n)*, making it efficient either.

It solves the problem of finding clusters in dense data. Also it solves the task of finding **number of clusters** by itself. Finally, in the input data there obviously are many outliers - noises. The algorithm marks such points as **noise**.

Advantages of DBSCAN:

- **Dynamically** finds cluster number and size, no need to find the number by hand
- **Noise** detection
- **Speed** and linear **complexity**
- Finds clusters in **dense and sparse** data
- **Non-hierarchical**

Disadvantages:

- Needs two parameters to be found to work. But this task may be automated for every new dataset.

The only two parameters needed for the algorithm to work are epsilon and number of neighbors.
