# Psychomotor Vigilance Task (PVT) for the NIBS Team

## Description

This PsychoPy experiment measures sustained attention and reaction time (RT) by requiring participants to press the **SPACEBAR** as quickly as possible when a red counter appears on the screen. 

This experiment is a fork of the original PsychoPy PVT experiment developed by Erik Marsja:  
[https://www.marsja.se/psychomotor-vigilance-task-psychopy-pvt](https://www.marsja.se/psychomotor-vigilance-task-psychopy-pvt)

## Instructions

1. A red counter will appear after a random delay.
2. Press the **SPACEBAR** as soon as you see the counter.
3. Avoid pressing too early; responses under **150 ms** are labeled as **False Starts**.

## Task Parameters

- **Duration**: 10 minutes (600 seconds)  
- **Inter-Stimulus Interval (ISI)**: Randomized between **2 and 10 seconds**  
- **Feedback**:  
  - RT displayed in milliseconds  
  - **"False Start!"** for early responses  
  - **"No Response!"** for missed trials  

## Output

The experiment saves trial data automatically in a `.txt` file during the experiment. Output files are saved in the `pvt_txt_data` directory with the following format:

`sub-<SubjectID>_PVT_data.txt`
