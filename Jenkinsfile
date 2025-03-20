
pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                script {
                    git branch: 'master', credentialsId: 'githubcredentials', url: 'https://github.com/yashikav123/devopsassignment2.git'
                }
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
