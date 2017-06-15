pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'This is build step'
        sh 'mvn package'
      }
    }
  }
}