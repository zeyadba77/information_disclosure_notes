# Information disclosure notes .
# some steps use to find information disclosure
# 1- check the source code 
## why check for source code ?
## Because it may lead to get some sensitive information like Api key or passwords also we can get operating system version and search for cves for current version
## we can find some important paths to look for or important java script files to learn more about source code Disclosure. 
## I suggest look at this article from portswigger..
## https://portswigger.net/kb/issues/006000b0_source-code-disclosure
# 2- check Robots.txt file 
##  why check for Robots.txt?
## because robots.txt tells search engines about allowed paths to view and disallowed pages which may have important information for us.
## I suggest look at this article from portswigger.
## https://portswigger.net/kb/issues/00600600_robots-txt-file
# 3- fuzzing 
## why fuzzing ?
## because fuzzing help us to discover important paths by using ffuf and wordlist there are also different tools like feroxbuster and dirsearch.
## personally I use this wordlist : https://github.com/maurosoria/dirsearch/blob/master/db/dicc.txt
## with ffuf  because it gives awesome results.

## If you find a path and you don't know if is important or not you can easily type path name + hackerone in google search and check if someone report it before or not.

# 4- google dorks 
## why using google dorks?
## simply google dorks is to use special keywords to search for specific webpages or some files
## you can read more about google dorks using this article
## https://gist.github.com/sundowndev/283efaddbcf896ab405488330d1bbc06

# 5- github dorks
## why using github ?
## we use github as bug hunters to search for any secret token or password or any valid credentials on source code realted to webssite project. 
## you can read more about github dorks using this article
## https://infosecwriteups.com/github-dork-553b7b84bcf4
## this website is helpful if you are looking for automated dorks https://dorks.faisalahmed.me/#
# 6 -java script file analsyis
## why to analayze js files?
## we analayze js files beacuse it may contain New endpoints,Hidden parameters,API keys, important paths to view
## if you want to read more about js file analasis you can use this article.
## https://medium.com/geekculture/analysing-javascript-files-for-bug-bounty-hunters-71e2727abebe

