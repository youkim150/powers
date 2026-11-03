
<!-- README.md is generated from README.Rmd. Please edit that file -->

# powers

<!-- badges: start -->

<!-- badges: end -->

The goal of powers is to enable users to easily calulate common powers
of numeric data

## Installation

You can install the development version of powers like so: Installation
can be done directly by calling:

``` r
devtools::install_github("youkim150/powers")
```

## Example

This is a basic example which shows you how to use the `square` function
from the `powers` package.

``` r
library(powers)

# Square a single numeric
square(4)
#> [1] 16

# Square a numeric vector
square(c(2,3,4))
#> [1]  4  9 16
```
