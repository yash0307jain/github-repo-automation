# SETUP - Add the file to the Environment Variable
### Batch File
- Add the location of folder where main batch file exist to the windows environment variable, in my case its
```
<FULL PATH>/windows
```

### Shell File
- Create the .bachrc file in the `C:/User/<User_name>` folder, then add this command to it with you folder location, in my case its
```
source <FULL PATH>/linux_mac/project.sh
```

# RUN
### Batch File
```
project <project_name>
```

### Shell File
```
project <project_name>
```