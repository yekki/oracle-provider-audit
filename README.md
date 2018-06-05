# Fixed
copy tools.jar from jdk lib to jre lib

# Deploy
    ant deploy

- It will copy SimpleSampleAuditor.jar to server lib mbeantypes folder. for example: /Users/gniu/Oracle/osb/wlserver/server/lib/mbeantypes/SimpleSampleAuditor.jar
- The jar file must also to be on the server's classpath, modify the startWeblogic.sh script manually