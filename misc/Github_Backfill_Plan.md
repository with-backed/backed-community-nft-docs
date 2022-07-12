## Backfill Github Script to Award Previously Merged PRs
We will also run a backfill script to award Contributor XP to all users who have merged a PR in _any_ Backed repository. This proposal file aims to garner feedback 
from the community regarding how many points each PR should be worth. 

Options are as follows:
1. 1 Contributor XP per PR merged. I.E. 5 Github PRs merged would translate to 5 Contributor XP. 
2. Fibonaccci sequence mapping. For every Nth Fibonacci number of PRs merged, 1 Contributor XP is awarded. I.E. A user would get 1 XP for their 1, 2, 3, 5, 8, 13, etc. PR
3. Expontential backoff, by powers of two. I.E. A user would get 1 XP for their 1, 2, 4, 8, 16, 32, etc. PR

Community feedback on which option to choose is very welcome! Let us know what you think in the comments of the PR.
