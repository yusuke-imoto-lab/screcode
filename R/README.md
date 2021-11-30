# scRECOCE for R code
The current version of the R code is not fast because the PCA algorithm on R is slow. We recommend using the python code for large-scale data. 

## Installation

You can install `scRECODE` on R with:

``` r
devtools::install_github("yusuke-imoto-lab/scRECODE/R")
```


## Example
For the single-cell data *X* (rows: genes, columns: cells), we can apply scRECODE as follows. 


``` r
library(scRECODE)

X.RECODE <- scRECODE(X)
```