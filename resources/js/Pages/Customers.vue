<script setup>
import { Head, Link } from '@inertiajs/vue3';


defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});

</script>

<template>
    <Head title="Products" />
    <header>
    <div class="px-3 py-2 text-white" style="background-image: linear-gradient(235deg, #001009 0, #00100b 4.55%, #00100d 9.09%, #00100f 13.64%, #001011 18.18%, #001012 22.73%, #001013 27.27%, #001014 31.82%, #000f15 36.36%, #000f16 40.91%, #000f17 45.45%, #000e17 50%, #020d17 54.55%, #040d17 59.09%, #070c17 63.64%, #090c17 68.18%, #0c0b17 72.73%, #0e0a16 77.27%, #100a16 81.82%, #120915 86.36%, #130914 90.91%, #150812 95.45%, #160811 100%);">
      <div class="container">
        <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
          <a href="/" class="d-flex align-items-center my-2 my-lg-0 me-lg-auto text-white text-decoration-none">
            <img src="/img/ynv.png" alt="logo YNV" width="50" height="50">
          </a>

          <ul class="nav col-12 col-lg-auto my-2 justify-content-center my-md-0 text-small">
            <li>
              <a href="/" class="nav-link text-white">
                <img class="bi d-block mx-auto mb-1" src="/img/home.svg" alt="home" width="24" height="24">
                Home
              </a>
            </li>
            <li>
              <a href="Panel" class="nav-link text-white">
                <img class="bi d-block mx-auto mb-1" src="/img/dashboard.svg" alt="home" width="24" height="24">
                Dashboard
              </a>
            </li>
            <li>
              <a href="Orders" class="nav-link text-white">
                <img class="bi d-block mx-auto mb-1" src="/img/order.svg" alt="home" width="24" height="24">
                Orders
              </a>
            </li>
            <li>
              <a href="Products" class="nav-link text-white">
                <img class="bi d-block mx-auto mb-1" src="/img/product.svg" alt="home" width="24" height="24">
                Products
              </a>
            </li>
            <li>
              <a href="customer" class="nav-link text-success">
                <img class="bi d-block mx-auto mb-1" src="/img/custom.svg" alt="home" width="24" height="24">
                Customers
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </header>
</template>


<style>

</style>
