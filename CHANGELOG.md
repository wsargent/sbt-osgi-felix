# Version 1.0.4

* Fix #3: Include unmanaged jars in bundle generation

# Version 1.0.3

* Fix: Ensure osgi dependencies of sbt dependant projects are included on Test classpath 
* Fix: Include osgi dependencies on Runtime classpath

# Version 1.0.2

* New `osgiPackageOBR` task for creating a self contained OBR
* Create a single instance of the Felix framework for calling into the bundle repository admin
* New `osgiShow` task for showing the start configuration
* New `osgiShowDeps` task for showing the reasons a plugin was resolved 

