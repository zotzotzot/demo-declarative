pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Another Example') {
            steps {
                echo 'Hello UCI'
            }
        }
    }
    post {  
        always {
            echo 'I will always say Hello again!'
        }
    }
}
