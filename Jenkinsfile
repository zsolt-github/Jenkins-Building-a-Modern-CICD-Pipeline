pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$GIT_BRANCH"
         }
      }
      stage('Docker Build') {
         steps {
            sh '''#!/bin/bash
                  echo "Hello World!"
                  docker images -a
               '''
         }
      }
   }
}
