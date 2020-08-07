# moPMR

moPMR(Probabilistic two sample mendelian randomization for multiple outcome traits),is an R package for efficient statistical inference of two-sample MR analysis. It can account for the correlated instruments and the horizontal pleiotropy, and can provide the
accurate estimates of both causal effect and horizontal pleiotropy effect as well as the two corresponding p values.

# Installation
It is easy to install the development version of PMR package using the 'devtools' package. The typical install time on a "normal" desktop computer is less than one minute.

```
# install.packages("devtools")
library(devtools)
install_github("yuanzhongshang/moPMR")
```


# Usage
There are two main functions in moPMR package, one is *moPMR_individual* for individual level data, the other is *moPMR_summary* for summary data.

You can find the instructions by '?moPMR_individual' and '?moPMR_summary'. 
```
library(moPMR)

?moPMR_individual

?moPMR_summary
```

# Example

One simple example to use the package can be found at https://github.com/yuanzhongshang/moPMR/tree/master/example

# Results reproduced 

All results from all methods used in the PMR paper can be reproduced at https://github.com/yuanzhongshang/PMRreproduce

# Development
This R package is developed by Zhongshang Yuan and Xiang Zhou.

