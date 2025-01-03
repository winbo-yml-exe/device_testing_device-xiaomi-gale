# Reference: <https://postmarketos.org/devicepkg>
pkgname=device-xiaomi-gale
pkgdesc="Xiaomi Redmi 13C"
pkgver=1
pkgrel=0
url="https://postmarketos.org"
license="MIT"
arch="aarch64"
options="!check !archcheck"
depends="
	linux-xiaomi-gale
	mkbootimg
	postmarketos-base
"
makedepends="devicepkg-dev"
source="
	deviceinfo
	modules-initfs
"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="
b13271effa518a8458badaa369867a616b92ee44c52669300b08a90c00c4de550d3f48ce3a85a99d76505e5cc86eec7b0f6b3f758533f74b78215e305bc412cb  deviceinfo
e70bae17df23dcaaaea0e2d3616556f04baa23f8ee1357785c0f539bf97282d8ddff53953e155b72689bb73beb38c2da3d08de2a61e866684edfa10a6593885d  modules-initfs
"
