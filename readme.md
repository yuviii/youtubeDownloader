#Download youtube video with the script

## To download the youtube video from cmd

Copy the Perl Scipt file dwn.pl to your local machine
	* Navigate to the location of the dwn.pl file
	* run the following command

./dwn.pl "youtubevideo_url"

for example ./dwn.pl "https://www.youtube.com/watch?v=IfaVLcdcitc"

> you can check how much file is downloaded by using the command **ls -la** as it has not option to see the progress.All the download undergoes in the background so you can download the multiple file at the same time. You can check which file are being downloading by using **ps | grep -i curl** command in the terminal.


