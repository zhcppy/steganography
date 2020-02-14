# steganography

golang Implementation LSB steganography any data

inspired by [stegify](https://github.com/DimitarPetrov/stegify)

Why duplicate implementations, Because I want to hide any data in the image, not just the image.

**This is just the beginning, I hope to get your advice**

## Install
    
    go get -v -u github.com/zhcppy/steganography/cmd/stego

or

    git clone https://github.com/zhcppy/steganography
    
    make install

## Use

    stego -h

## Extension

Implementing interface about Steganography 
    
    type Steganography interface {
    	GetCarrierFileName() string // get image carrier
    	InputData() ([]byte, error)
    	OutputData(data []byte) error
    }
    
    
## About me(https://zhcppy.github.io)
