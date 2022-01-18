# Cryptocurrencies
## Overview
The purpose of this project is to use unsupervised machine learning to analyze cryptocurrencies and create reports showing the traded cryptocurrencies grouped accroding to their features. This report could be used by investment bankers to propose new cryptocurrency investments to their clients. In order to analyze the data we used the following methods:
- Preprocessing the database
- Reducing the data dimension using Principoal Component Analysis
- Clustering Cryptocurrencies using K-Means
- Visualizing Classification results with 2D and 3D scatter plots
## Results
After we preprocessed and cleaned the cryptocurrency data, there are a total of 532 tradable cryptocurrencies.
![This is an image](https://github.com/weise142/Cryptocurrencies/blob/main/images/tradable%20crypto.PNG)
From these 532 tradable cryptocurencies we also created a table of tradable cryptocurrencies and added classes to them. As can be seen in the picture, most of the cryptocurrencies are in class 0 or 3:
![This is an image](https://github.com/weise142/Cryptocurrencies/blob/main/images/Tradable%20crypto%20table.PNG)
### Clustering Cryptocurrencies using K-Means and Elbow Curves
In order to identify clusters within the data we plot an elbow curve to determine what the best K value will be:
![This is an image](https://github.com/weise142/Cryptocurrencies/blob/main/images/Elbow%20Curve.PNG)
As can be seen in the elbow chart, the best K-Value is 4 so we will use 4 clusters to categorize the cryptocurrencies.
### Visualizing Results
Below is a 3D scatter plot with clusters. The plot was obtained using the PCA algorithm which reduced the cryptocurrency dimensions to three principal components:
![This is an image](https://github.com/weise142/Cryptocurrencies/blob/main/images/3D%20scatter.PNG)
Next we looked at two important features of cryptocurrencies, Total Coin Supply versus Total Coins Mined. For this we created a 2D scatterplot with Total Coin Supply on the Y axis and Total Coins Mined on the x axis. We can see based on this chart that most cryptocurrencies are clustered in the bottom left of the chart meaning little of the supply has been mined:
![This is an image](https://github.com/weise142/Cryptocurrencies/blob/main/images/2D%20scatter%2C%20total%20coins%20mined%20vs%20total%20coin%20supply.PNG)
## Summary
Based on the above analysis, we have narrowed down our data of cryptocurrencies to tradable cryptocurrencies only and grouped them by the similarioty of their features. We could continue looking into further groupings based on different data points and further narrow down the most worhty cryptocurrency investments for Accountability Accountings clients.
