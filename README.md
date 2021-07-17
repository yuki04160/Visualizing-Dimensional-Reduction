# Visualizing Dimensional Reduction
To visualize high-dimensional dataset, I conducted an unsupervised machine learning algorithm, t-SNE, in Python using GitHub dataset [fashion-minst](https://github.com/zalandoresearch/fashion-mnist), which is an image pixel dataset.
## Introduction
The same as PCA (Principal Component Analysis), t-SNE (t-distributed Stochastic Neighbor Embedding) is an unsupervised machine learning algorithm. PCA is a linear dimensionality reduction algorithm, while t-SNE is a non-linear dimensionality reduction algorithm. Yet, both of them can be used for exploring high-dimensional data. Thus, this project aims to visualize high-dimensional data in two dimensions using t-SNE. 

The dataset is related to Zalando's article images. There are total of 10,000 examples and each example is a 28x28 grayscale image associated with a label from 10 classes. That is, there are 10 kinds of fashion products.
## Data Analysis
   - Change label name using Dictionary
   - Plot product images
   - View the distribution of labels
   - Visualize dimensional reduction
     - Instead of using the whole dataset, I generated a subset of data with 100 random samples for each fashion product
     - I used TSNE function from sklearn to reduce the dimension of the data down to 2
     - I generated a plot to visualize the dimension-reduced dataset
       - Instead of using dots, I used the number of the fashion product in the plot and used different colors for different fashion products.
## Conclusion 
