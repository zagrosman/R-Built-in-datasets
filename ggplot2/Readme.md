# Pre-defined Datasets from the ggplot2 Package

In this folder, you can access pre-defined datasets from the **ggplot2** package. All these files have been extracted from this software package and can serve as a great resource for learning **R programming** as well as working with the **ggplot2** package.

Please note that all of these files are in **.csv format**, and you can open any of them using **Excel** and then use them in **R**. Given that having the correct data format is essential for performing statistical and graphical analyses in **R**, these predefined datasets will allow you to quickly learn how to work with **R**. Additionally, you can use these datasets as a reference for formatting your own data correctly.

## Data Extraction Using Clipr R Package

All of these datasets have been extracted using the following R package, in accordance with the sample code provided for this tool. Users can use the following code to download and save other predefined datasets from R packages.

```r
install.packages("clipr")  
library(clipr)  
dat <- mtcars[1:5, c(3:4, 8:11)]  
dat  
write_clip(dat)
