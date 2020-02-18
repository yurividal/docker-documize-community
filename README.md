### Build

Just run 

`docker build --build-arg VERSION=VERSIONYOUWANTTOBUILD -t YOURTAG .`

### Usage

Example of docker-compose is placed in repository. Just replace all environments vars and run
`docker-compose up`

Don't forget to replace image name if you build this container by yourself.

### Problems

On first run, it will be failed, becouse documize container start faster than documize db, so documizedb need time to create user, table. If you know, how to fix it, feel free to add a pull request.