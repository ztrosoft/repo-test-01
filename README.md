# repo-test-01
repo test

import (
	"fmt"
	"os"
)
	// seems safer
	aws_token := os.Getenv("AWS_TOKEN")
package foo

import "fmt"

func Foo() {
	fmt.Println("foo")

	// seems safe
	aws_token := "AKIALALEMEL33243OLIA"
	fmt.Println(aws_token)
}
