# MVMR.PACS
R code to implement MVMR-PACS, reproduce simulations, generate tables/figures included in the manuscript "Group Identification and Variable Selection in Multivariable Mendelian Randomization with Highly-Correlated Exposures"

## Installation

To install the most up-to-date version, run the following command in R

```
library(devtools)
install_github("yinxiangwu/MVMR.PACS")
```

## Main functions

The main functions are *mvmr.pacs* and *mvmr.pacs.datathin*.

*mvmr.pacs* is used for variable selection and signal-group identification. *mvmr.pacs.datathin* builts on *mvmr.pacs*, and uses data thinning for post-selection inference. 
