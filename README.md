
Model Comparison In Approximate Bayesian Computation

Compa-ABC is a Python package for performing model comparison in Approximate Bayesian Computation. 
It enables you to do Bayesian model comparison between models for which a likelihood function is 
not available. In contrast to previous approaches that are mainly based on variants of rejection sampling,
this is a density estimation method that approximates the posterior over models in parametric form 
using a mixture-density network. 

# Documentation 
## Installation 
Clone the repository. Then, in the repository root folder, run 

    python setup.py install --user 
    
to install all required packages. Alternatively, you install it via ``pip`` using 

    pip install git+https://github.com/janfb/mcabc.git --process-dependency-links

To test whether everything worked out fine, run 

    nosetests tests/
    
in the repository root folder.

## Examples
You find a jupyter notebook in the ``examples`` folder presenting the methods on a tractable
example problem: Bayesian model comparison between a Poisson model and a negative binomial model. 
More examples will follow soon. 
