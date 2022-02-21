# Australia Fires and Climate Change Dataviz

## Introduction
The 2019-2020 Australia fires has drawn attention of the whole world, which is the worst in Australian history. It is estimated that the fires led to the deaths of at least 33 people and over 3 billion animals. Therefore, I would like to do some analysis in this project about Australian climate change over time and recent fires . The dataset is from [TidyTudesday Project](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-01-07/readme.md). The purpose is to practice a wide variety of data visualization techniques, and gain some insights from the data.

You can read more details about how the script works in this [document](https://rpubs.com/xibei_chen/australia_fires_and_climate_change) published on RPubs.

## Data Source
There are three datasets I used for this analysis:

rainfall provides everyday rainfall data including city name, date, rainfall volume, period, quality, latitude, longitude for a few main cities in Australia from 1858 to 2020. (167513 observations)
temperature provides everyday temperature data including city name, date, maximum temperature and minimum temperature for a few main cities in Australia from 1910 to 2019. (524813 observations)
nasa_fire provides fire data including brightness, acquisition date and time, satellite, day or night etc for every fire captured by NASA. (34270 observations)

## Climate Change Analysis
Below are the EDA objectives:
+ Distribution of Max and Min Temperature across Cities
+ Distribution of Annual Rainfall Volume across Cities
+ Correlation between Temperature and Rainfall Volume

Through furtherdata analysis and visualization, I want to answer the following questions:
+ How did rainfall volume change over years in the 21st century?
+ How did temperature change over years in the 21st century?

## Conclusion
As stated in the [New York times article](https://www.nytimes.com/interactive/2020/01/02/climate/australia-fires-map.html):
>“[Crystal A. Kolden, a wildfire researcher (formerly) at the University of Idaho] says the combination of extremely dry and extremely hot conditions adds up to more powerful fires.”

With analysis and visualizations, there was indeed an increasing trend in temperature and a drastic drop in rainfall volume across all the main Australian cities in 2019. And the correlation of extreme weather and fire occurrence is alleged to be positive. I hope the heart-rending fire disaster would raise people’s awareness of the recent extreme weather. To protect our planet and all the beautiful creatures on this land from climate disasters like wildfire, we should do our best to reduce carbon footprint to better tackle climate change.
