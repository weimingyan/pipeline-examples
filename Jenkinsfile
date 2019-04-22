pipeline {
  agent {
    docker {
      image 'node:latest'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'echo \'hello build\''
      }
    }
  }
}