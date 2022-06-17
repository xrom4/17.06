# 17.0

    import requests
    
    
    print(requests.get('https://fakestoreapi.com/'))

    print(requests.get('http://fakestoreapi.com/docs'))

     print(requests.post('https://fakestoreapi.com/users'))
  
   print(requests.post('https://fakestoreapi.com/products/7'))

   print(requests.get('https://donate.keikaavousi.com/'))

    print(requests.get('https://fakestoreapi.com/products/category/jewelery'))

    print(requests.get('https://fakestoreapi.com/carts'))

    print(requests.get('https://fakestoreapi.com/users'))

    print(requests.get('https://fakestoreapi.com/auth/login'))

#print(requests.get('https://fakestoreapi.com/carts/5'))
#r = requests.get('https://fakestoreapi.com/carts/5')
#print(r.json())

    print(requests.get('http://fakestoreapi.com/products'))
    r = requests.get('http://fakestoreapi.com/products')
    print(r.json())
