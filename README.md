# FMA-Dataset-For-Auto-Genre-classification
Capable of automatically categorizing audio files from the FMA dataset into their respective genre folders.
This document utilizes the dataset provided by the Free Music Archive (FMA), which can be found at FMA GitHub repository. The script is designed for automated genre classification; it organizes music files from the tracks.csv according to their genre, placing each track into the corresponding folder. This organization facilitates subsequent data processing or model training activities.

The FMA dataset is divided into several sizes:

Small (7.2 GiB)
Medium (22 GiB)
Large (93 GiB)
Full (879 GiB)

After downloading and extracting the dataset into a directory, set the directory path as the AUDIO_DIR in the Python script. Next, update the path to the downloaded tracks.csv by modifying the tracks variable in the script. Once these paths are configured, executing the code will distribute all music files into folders based on their respective genres, making them readily available for further processing or training models.
