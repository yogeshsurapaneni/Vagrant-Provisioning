pipeline {
    agent { label 'master' }
    stages {
       stage('build') {
          checkout scm
          steps {
             bat 'dir'
             bat 'cd C:\\ '
             bat '''
                echo 'Multiline'
                echo 'Example'
                dir
             '''
             echo 'not using shell'
          }
       }
    }
}
