# Progressive GHOST experiments

This repository contains code and results for ablation studies run on the GHOST-v2 (GHOST + CHAOS) algorithm.

## Files

* `old-logs/` - The name is a misnomer; the logs are current, but were part of a smaller ablation study.
* `ghost-log/` - Log files generated in tuning. These are not particularly important (and neither is the above)
* `runs-*.txt` - The results of the ablation studies, containing the results.
* `steps.py` - Code to run experiments. Some of the configs may not correspond exactly to the code in analysis, since it was changed.
* `Analysis.ipynb` - Analysis of the results.

## Code

The `steps.py` code uses the `raise-utils` package, a high-level library built for convenience and standards enforcement. It can be installed via `pip3 install raise-utils`. See the [GitHub repo](https://github.com/yrahul3910/raise) for details.

## Cite this work

[Improving Deep Learning for Defect Prediction (using the GHOST Hyperparameter Optimizer)](https://arxiv.org/abs/2008.03835)

```
@misc{yedida2020improving,
      title={Improving Deep Learning for Defect Prediction (using the GHOST Hyperparameter Optimizer)}, 
      author={Rahul Yedida and Tim Menzies},
      year={2020},
      eprint={2008.03835},
      archivePrefix={arXiv},
      primaryClass={cs.SE}
}
```
