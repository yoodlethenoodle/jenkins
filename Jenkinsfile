pipeline {
    agent {
        docker {
                image 'python:3.10.1-alpine'
                label 'my-defined-label'
                args '-v /tmp:/tmp'
                }
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
