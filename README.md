# dummyhist
 dummy 2D-histogram generator


## Overview

 `dummyhist` is a script to generate random 2D-histogram.
 [ROOT](https://root.cern.ch) is used to show histograms.


## Requirement
 - python (> 3.9.9)
    - numpy (> 1.21.5)
    - scipy (> 1.7.3)
 - [ROOT](https://root.cern.ch) (> 6.24/06)


## Usage
 Users can run this program just running following command.

 ```
 $ dummyhist
 ```

 The next histogram will generated, when you press enter key.

 If you want to quit the program, you only have to send SIGTERM to the process (E.g. pressing Ctrl-C).


## Features
 Data samples are generated from variable number of normal distributions whose variance-covariance matrices are randomly generated with Wishart distribution.

 The mixing ratio between those clusters is generated from Dirichlet distribution.
 Those hyper parameters for Wishart distribution and Dirichlet distribution are fixed, but they can be changed by user.
 The probablity distributions are supported by `scipy.stats`.

<!--
## Reference
-->

## Author
 [yoshphys](https://github.com/yoshphys)

## Licence
 dummyhist is under MIT license. See the [LICENSE](https://github.com/yoshphys/dot2pdf/blob/main/LICENSE) for more info.
