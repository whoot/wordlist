# Wordlist

Wordlist useful for content discovery with Burp - contains 92.333 directories and files

Sorted and without duplicates, but probably with a lot of trash left ;)

Combines the following wordlists from [SecLists/Discovery/Web-Content/](https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web-Content)

```
Apache.fuzz.txt
ApacheTomcat.fuzz.txt
CGI-XPlatform.fuzz.txt
CGIs.txt
Common-DB-Backups.txt
CommonBackdoors-*.txt
Common-PHP-Filenames.txt
IIS.fuzz.txt
JRun.fuzz.txt
Jenkins-Hudson.txt
KitchensinkDirectories.fuzz.txt
Logins.fuzz.txt
OracleAppServer.fuzz.txt
Passwords.fuzz.txt
Randomfiles.fuzz.txt
RobotsDisallowed-Top*.txt
apache.txt
big.txt
common.txt
jboss.txt
nginx.txt
quickhits.txt
oracle.txt
raft-large-files.txt
raft-large-directories.txt
ror.txt
tomcat.txt
```

Also did the following:

 - removed/adjusted entries with , [ ] ! * % ../ < > ? } sex porn .gif .jpg .bmp .rss logout
 - removed entries with company reference (ebay, youtube, yahoo, ikea, amazon, ip-addresses)
 - removed entries with version numbers
 - removed some non-sense entries
 - removed leading /
 - added / at the end of a directory
