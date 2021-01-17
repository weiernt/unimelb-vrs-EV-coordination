# unimelb-vrs-EV-coordination
Coordinating the charging behaviour of electric-vehicles, done as part of The University of Melbourne's Math and Stats Vacation scholarship.

Modelling based on the paper "Semi-decentralized generalized Nash equilbrium seeking in monotone aggregative games" by Belgioioso and Grammatico, which can be found [here](https://arxiv.org/abs/2003.04031).

Mainly implements the game formulation in section V of the paper, using the *linear price function* rather than the *monotone price function*. 

Includes the following algorithms implemented:
- Algorithm 1: preconditioned forward-backward
- Algorithm 1B: inertial preconditioned forward-backward
- Algorithm 5: inertial forward-reflected-backward

## Libraries used:
- cvxopt
- numpy
- matplotlib