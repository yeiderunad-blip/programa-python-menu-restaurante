# MATRIZ DEL MENÚ

menu = [
    ["Hamburguesa", "Comida Rapida", 25000],
    ["Pizza", "Comida Rapida", 32000],
    ["Ensalada", "Saludable", 18000],
    ["Jugo Natural", "Bebidas", 12000],
    ["Pasta boloñesa", "Italiana", 35000],
    ["Lasagna", "Italiana", 40000]
]

# VARIABLES
categoria_objetivo = "Italiana"
umbral_precio = 30000
descuento = 0.15


# FUNCIÓN
def calcular_precio_final(categoria, precio):

    if categoria == categoria_objetivo and precio > umbral_precio:
        precio_final = precio - (precio * descuento)
    else:
        precio_final = precio

    return precio_final


# SALIDA
print("===== MENÚ DEL RESTAURANTE =====\n")

for producto in menu:

    nombre = producto[0]
    categoria = producto[1]
    precio_base = producto[2]

    precio_final = calcular_precio_final(categoria, precio_base)

    print("Producto:", nombre)
    print("Categoría:", categoria)
    print("Precio Base: $", precio_base)
    print("Precio Final: $", precio_final)
    print("--------------------------------")
