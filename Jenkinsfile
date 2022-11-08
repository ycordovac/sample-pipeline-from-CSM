pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script{
                    def cowsay=load lib/cowsay.groovy
                    cowsay.template("cosas")
                }
                echo 'Building.'
            }
        }
        
    }
}

