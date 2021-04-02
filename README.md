#**PyBer_Analysis**
##**Overview of the analysis**
In this project, we analyse the data we have collected from PyBer, a ride sharing company. In this analysis, we have created multiple data frames and charts using Pandas, Matplotlib, NumPy, and Scipy libraries and visualisations. The analysis has been done on the datasets during a specific period of time, starting from January to early May 2019. We used two .csv datasets, City data and Ride data, in our calculations and evaluated the ride-sharing data and total weekly fares.
##**Results**
Merging the two datasets and comparing the total number of drivers, rides, and fare amounts in one data frame shows that the number of riders and fares are relatively higher in Urban cities than the Suburban and Rural cities, e.i. respectively almost twice the suburban cities and about 9 to 13 times more than the Rural cities. Whereas, the number of drivers in Urban cities is approximately 30 times more than the Rural drivers and 4 times the Suburban drivers.

![PyBer_summary_df.png](https://github.com/zkt2018/PyBer_Analysis/blob/main/Resources/PyBer_summary_df.png)

This huge discrepancy between the data of the three city types results in lower average fares in Urban cities rather than Rural and Suburban cities. Average fare per driver in Rural cities is more than 3 times higher compared with the Urban cities average fare per driver. 

To get a more detailed data display, we used the loc method to sum up the total weekly fares for each city type.

![Weekly_Total_Fare.png](https://github.com/zkt2018/PyBer_Analysis/blob/main/Resources/Weekly_Total_Fare.png)

Based on this data frame, the non-null values in Rural cities are too lower than the non-null values in Urban cities, which explains the fact that in rural cities there have been a much lower number of ride shares than in urban or suburban cities (114 vs. 1509 and 573)
##**Summary**
According to our line chart which is built based on the weekly total fares, the fares are fluctuating slightly in all city types. However, according to the average fare per driver and and per ride the ride cost is much higher in rural areas than in cities. This can lead to lower interest of the people in using the ride share in suburban and rural areas.
![PyBer_fare_summary.png](https://github.com/zkt2018/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
