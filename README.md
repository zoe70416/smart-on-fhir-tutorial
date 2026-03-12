


launch.html
launch.html is the SMART app’s initial entry point and in a real production environment, would be invoked by the application launching your SMART app (for instance, the EHR or patient portal). In the SMART documentation, this is your app’s “launch URL”. In this tutorial, this page will be invoked when you launch your app from Cerner’s code console. 

As the entry point into your SMART app, this page will kick-off the SMART authorization workflow.

launch-patient.html

Similar to the launch.html above, this file is the entry point when launching a standalone patient application. This file was created for convenience factor. In production, you may want to create a separate app for patient facing vs provider facing version of the app. More info on this in Standalone App Launch for Patient Access Workflow section.

launch-smart-sandbox.html

This is a clone of the launch.html above. This file was created for convenience factor to allow you to use the same app to configure it against the SMART Health IT Sandbox. More info on this in Run your app against SMART Health IT Sandbox section.

index.html

This page will be invoked via redirect from the Authorization server at the conclusion of the SMART authorization workflow. When this page is invoked, your SMART app will have everything it needs to run and access the FHIR API.


The SMART app will be available at: https://zoe70416.github.io/smart-on-fhir-tutorial/example-smart-app

