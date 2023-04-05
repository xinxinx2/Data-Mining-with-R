# Data-Mining-with-R
Introduction:

The objective of this project is to cluster 325 metropolitan cities in the United States based on a set of numeric variables. 4867 number of data with size 66kb. The purpose of clustering is to group similar cities together and identify patterns in the data. This information can then be used to gain insights into factors that may be contributing to the similarities and differences between the cities.
<img width="1245" alt="image" src="https://user-images.githubusercontent.com/108433979/230231346-85b667d9-5677-4596-bcfc-8fc126e299e8.png">

The project uses two different clustering algorithms: K-means clustering and hierarchical clustering. K-means clustering is a commonly used partition-based clustering algorithm that aims to group similar data points into a predetermined number of clusters. Hierarchical clustering, on the other hand, is a dendrogram-based clustering algorithm that generates a tree-like structure to visualize the relationships between data points.

The data is preprocessed by removing non-numeric variables and scaling the numeric columns to ensure that each variable is on the same scale. The scaled data is then used as input to the clustering algorithms. In K-means clustering, the optimal number of clusters is determined using the total within-cluster variation (TWCV) and the elbow method. In hierarchical clustering, the number of clusters is determined by cutting the dendrogram at a specified height.
<img width="840" alt="image" src="https://user-images.githubusercontent.com/108433979/230231206-9de8504f-c699-492f-9566-5d6f831229e1.png">

Overall, this project aims to identify distinct clusters of metropolitan cities based on their numeric characteristics, and provide insights into the factors that may be contributing to these similarities and differences. The results of this analysis can be useful for urban planners, policymakers, and researchers who are interested in understanding the differences and similarities between metropolitan cities in the United States.

<img width="896" alt="image" src="https://user-images.githubusercontent.com/108433979/230231225-8fefa638-1602-4cda-9e86-8854fa1e6e2d.png">

Overall, this project aims to identify distinct clusters of metropolitan cities based on their numeric characteristics, and provide insights into the factors that may be contributing to these similarities and differences. The results of this analysis can be useful for urban planners, policymakers, and researchers who are interested in understanding the differences and similarities between metropolitan cities in the United States.
