Fork of [Monte Python](https://github.com/brinckmann/montepython_public) with a logflat prior.

```python
data.parameters['sigma_dmeff'] = [1e-28, 1.e-30, 1e-18, 1e-20,	1, 'cosmo', 'logflat']
```



----

# Monte Python, a Monte Carlo Markov Chain code (with Class!)

* Main developer: Thejs Brinckmann <brinckmann@physik.rwth-aachen.de>
* Aithor: Benjamin Audren <benjamin.audren@epfl.ch>
* License: MIT


The code is under the MIT license. As an additional clause, when using the code
in a scientific publication you are also required to cite the v3.0 release paper
``MontePython 3: boosted MCMC sampler and other features`` and the original release
paper ``Conservative Constraints on Early Cosmology`` (see the tail of this document
for the bibtex entries).



# Bibtex entry

When using *Monte Python* in a publication, please acknowledge the code by citing
the following papers. If you used *Class*, *MultiNest*, *PolyChord* or *Cosmo Hammer*,
you should also cite the original works.

Please also cite the relevant papers for each likelihood used: as of v3.0 we have a
list of references for all likelihoods in the first of the papers below. In the
future the list will be maintained on the official `Monte Python website
<https://brinckmann.github.io/montepython_public/>`_. Otherwise, this information can
often be found in the .data file of the likelihood folder.

In order to encourage people to both develop and share likelihoods with the community,
to the benefit of all users, we optionally encourage users to cite the paper in which
the *Monte Python* likelihood was first used, in addition to the papers in which data
and/or likelihoods were published.

```

    @article{Brinckmann:2018cvx,
          author         = "Brinckmann, Thejs and Lesgourgues, Julien",
          title          = "{MontePython 3: boosted MCMC sampler and other features}",
          year           = "2018",
          eprint         = "1804.07261",
          archivePrefix  = "arXiv",
          primaryClass   = "astro-ph.CO",
          SLACcitation   = "%%CITATION = ARXIV:1804.07261;%%"
    }
    @article{Audren:2012wb,
          author         = "Audren, Benjamin and Lesgourgues, Julien and Benabed,
                            Karim and Prunet, Simon",
          title          = "{Conservative Constraints on Early Cosmology: an
                            illustration of the Monte Python cosmological parameter
                            inference code}",
          journal        = "JCAP",
          volume         = "1302",
          pages          = "001",
          doi            = "10.1088/1475-7516/2013/02/001",
          year           = "2013",
          eprint         = "1210.7183",
          archivePrefix  = "arXiv",
          primaryClass   = "astro-ph.CO",
          reportNumber   = "CERN-PH-TH-2012-290, LAPTH-048-12",
          SLACcitation   = "%%CITATION = ARXIV:1210.7183;%%",
    }
```
