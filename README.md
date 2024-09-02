# FKITA:Fuzzy Knowledge Inference Based Dynamic Task Allocation Method for Multi-Agent Systems
## Note

## Installation instructions
* Set up StarCraft II and SMAC:
Follow the Quick Start in https://zhuanlan.zhihu.com/p/627016542.

* Set up Google Research Football:
Follow the Quick Start in https://github.com/google-research/football.

* Set up Multi-Agent Particle Environments:
Follow the Quick Start in https://github.com/openai/multiagent-particle-envs.

## Run an experiment
### StarCraft Multi-Agent Challenge
```shell
python3 src/main.py --config=fkita --env-config=sc2 with env_args.map_name=2s3z env_args.seed=1
```

### Google Research Football
```shell
python3 src/main.py --config=fkita --env-config=academy_3_vs_1_with_keeper with seed=1
```

### Multi-Agent Particle Environments
```shell
python3 src/main.py --config=fkita --env-config=mpe_env with scenario_name=simple_tag seed=1
```

The config files act as defaults for an algorithm or environment.

They are all located in src/config. 

--config refers to the config files in src/config/algs --env-config refers to the config files in src/config/envs

All results will be stored in the Results folder.

## Saving and loading learnt models

## Watching StarCraft II replays