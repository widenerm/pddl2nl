# pddl2nl

This repository contains code for converting select Planning Domain Definition Language (PDDL) files into natural language (NL) prompts. The project includes Python scripts for conversion alongside converted prompts in NL for training and testing.

## Conversion Scripts
- [**blocks_NL_converter.py**](https://github.com/widenerm/pddl2nl/blob/main/blocks_NL_converter.py): Python script for converting blocksworld PDDL problem files to natural language prompts.
- [**driverlog_NL_converter.py**](https://github.com/widenerm/pddl2nl/blob/main/driverlog_NL_converter.py): Python script for converting driverlog PDDL problem files to natural language prompts.
- [**gripper_NL_converter.py**](https://github.com/widenerm/pddl2nl/blob/main/gripper_NL_converter.py): Python script for converting gripper PDDL problem files to natural language prompts.
- [**miconic_NL_converter.py**](https://github.com/widenerm/pddl2nl/blob/main/miconic_NL_converter.py): Python script for converting miconic PDDL problem files to natural language prompts.
- [**movie_NL_converter.py**](https://github.com/widenerm/pddl2nl/blob/main/movie_NL_converter.py): Python script for converting movie PDDL problem files to natural language prompts.

## Training Problems
- [**train_NL_problems.zip**](https://github.com/widenerm/pddl2nl/blob/main/train_NL_problems.zip) contains natural language prompts converted from [**downward-benchmarks**](https://github.com/aibasel/downward-benchmarks/tree/master) in the five domains listed above (excluding assembly) using their corresponding script.

## Test Problems
- [**test_NL_problems.zip**](https://github.com/widenerm/pddl2nl/blob/main/test_NL_problems.zip) contains natural language prompts converted from problems generated by [**pddl generators**](https://github.com/AI-Planning/pddl-generators) in the five domains listed above (excluding assembly) using their corresponding script.
