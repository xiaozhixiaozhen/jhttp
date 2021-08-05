  
### Demo
Change the the backround color in the following file by swapping the comments in the below file.
* [Change background color](src/main/java/io/harness/jhttp/processor/DirectoryListing.java)

The change should look like this:

![image](https://user-images.githubusercontent.com/63068621/128278014-1b9beeb7-2f9d-4a23-9c3f-0e02a3905739.png)

Create a pull request

Click the "details" button on the status of your pull request, it will bring you to the demo environment running your build

![image](https://user-images.githubusercontent.com/63068621/128278134-6ed16f6d-5a10-4db1-8641-8c91eb6cfe82.png)


## Notes:

    mvn clean package will build the application
 
It creates a self-contained, executable JAR in the `target` directory.

## Usage

    usage: java -jar jhttp*.jar [-h] [-p <PORT>] [-r <DIR>] [-t <THREADS_NO>]
    Starts a simple HTTP server
    -h,--help                   display help
    -p,--port <PORT>            port to listen (default: 8888)
    -r,--root <DIR>             server root directory (default: '.')
    -t,--threads <THREADS_NO>   thread pool size (default: 10)
 
