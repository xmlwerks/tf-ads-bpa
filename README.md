[![Build Status](http://18f-dari.techflow.com/jenkins/job/tf-ads-bpa-build/badge/icon)](http://18f-dari.techflow.com/jenkins/job/tf-ads-bpa-build/)

# Prototype

A publicly accessible prototype is hosted at
[http://18f-dari.techflow.com](http://18f-dari.techflow.com/).

# Documentation

* [Maven Site](http://tflowgit.github.io/tf-ads-bpa/1.0-SNAPSHOT/)
* [Swagger API Documents](http://18f-dari.techflow.com/swagger/)
* [SonarQube Reports](http://18f-dari.techflow.com/sonarqube/dashboard/index/1)
* [Javadoc](http://tflowgit.github.io/tf-ads-bpa/1.0-SNAPSHOT/apidocs/index.html)

# Source Code

https://github.com/TFlowGit/tf-ads-bpa.git (branch=master)

# Build from Source

Pre-requisites:
- [Maven](https://maven.apache.org/download.cgi#Installation)
- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [OpenJDK](http://openjdk.java.net/install/)

To build the project from source, check out the code from GitHub and
build it with Maven. This creates a JAR file that can be run.

    git clone https://github.com/TFlowGit/tf-ads-bpa.git
    cd tf-ads-bpa
    mvn package
    java -jar openfda-web/target/openfda-web-1.0-SNAPSHOT.jar

Browse to [http://localhost:8080](http://localhost:8080).

# Run from Eclipse

    git clone https://github.com/TFlowGit/tf-ads-bpa.git

Import the project into Eclipse (File -> Import -> Existing Maven Projects)

Run the class `com.techflow.openfda.OpenFdaApplication` as Java in the
`openfda-web` project.

Browse to [http://localhost:8080](http://localhost:8080).

# License

All code created for this project is licensed under the CC0
license. Please read [LICENSE.md](LICENSE.md) for details.

Please see [LICENSES.md](LICENSES.md) for a list of all software used
as a part of this project.
