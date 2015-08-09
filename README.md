# RaspbianTimeLapse
Simple time lapse using crontab (takes pictures at set intervals)

Sudo crontab -e

add the following to the crontab which will take a picture every min. Note that the minimum interval you can get with crontab is 1 min:

* * * * * /home/pi/projects/timelapse/timelapse.sh 2>&1
