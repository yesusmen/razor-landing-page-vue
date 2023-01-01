<script setup>

import ArrowRightIcon from './icons/arrow-right.svg';
import AppIcon from './icons/apple.svg'
import PlayStoreIcon from './icons/play-store.svg'

</script>

<template>
  <div class="relative min-h-screen w-full bg-gray-800 text-white">

    <img src="/img/circle.svg" alt="" class="absolute top-0 left-0 -translate-x-1/4 -translate-y-1/4 opacity-40" />

    <div class="absolute inset-y-0 w-2/5 bg-gray-900 right-0"></div>

    <div class="relative mx-auto max-w-7xl px-4 pt-8">
      <nav class="flex items-center justify-between">

        <div class="flex items-center gap-32">
          <a class="text-2xl font-bold" href="#">Razor</a>
    
          <ul class="flex items-center gap-12 font-medium text-gray-500">
            <li><a href="#" class="hover:text-white">Product</a></li>
            <li><a href="#" class="hover:text-white">Resorces</a></li>
            <li><a href="#" class="hover:text-white">Support</a></li>
            <li><a href="#" class="hover:text-white">Princing</a></li>
          </ul>
        </div>
  
        <div class="flex items-center gap-4 font-medium text-gray-500">
          <a href="#" class="hover:text-white">Sign In</a>
    
          <a href="#" class="relative hover:text-white">
            <span>Request Demo</span>
            <img src="/img/decoration.svg" alt="" class="absolute left-0 w-32"/>
          </a>
        </div>
  
      </nav>   
      
      <div class="grid grid-cols-2 pt-6">

        <div class="max-w-xl pr-24">

          <div class="w-48 border-t border-gray-700 pt-2 flex items-center gap-6">
            <span class="text-sm font-normal text-teal-500">
              entas@dev-jeag.com
            </span>
            <ArrowRightIcon class="h-4 w-4 text-teal-500"/>
          </div>

          <div class="pt-16">
            <span>&#8212; Get the App</span>

            <h1 class="pt-6 text-6xl font-bold tracking-tight bg-gradient-to-r from-blue-400 to-emerald-400 bg-clip-text text-transparent">
              Enter your email <br/>
              &#8212; We'll send you a download link
            </h1>

            <img src="/img/decoration.svg" alt="" class="-mt-2 w-96"/>

            <div class="flex items-center mt-10 shadow-glow focus-within:shadow-teal-500/40 rounded-xl transition-shadow ease-out">

              <input type="text" class="flex-1 px-8 py-4 border-2 border-r-0 rounded-l-xl border-gray-700 bg-gray-900 leading-6 focus:outline-0" placeholder="Sales@dstudio.digital">

              <button class="border-2 border-l-0 rounded-r-xl border-gray-700 px-8 py-4 bg-teal-500 font-bold text-lg leading-6 text-black">
                Get Link
              </button>

            </div>

            <p class="pt-8 font-normal tracking-wide text-gray-600">
              By signing up, I agree to the Razor 
              <a href="#" class="text-gray-500 underline">Privacy Policy</a> & 
              <a href="#" class="text-gray-500 underline">Terms of Service</a>
            </p>

            <div class="flex items-center gap-4 pt-12">
              <button class="flex items-center gap-2 px-6 py-4 text-gray-500 rounded-xl bg-gray-900 shadow-glow hover:shadow-teal-500/40 transition ease-out hover:-translate-y-1">
                <AppIcon class="h-7 w-7"/>
                App Store
              </button>
              <button class="flex items-center gap-2 px-6 py-4 text-gray-500 rounded-xl bg-gray-900 shadow-glow hover:shadow-teal-500/40 transition ease-out hover:-translate-y-1">
                <PlayStoreIcon class="h-7 w-7"/>
                Play Store
              </button>
            </div>
          </div>

        </div>

        <div class="pt-10">
          <div class="flex justify-center gap-8">
            <img src="/img/screen-1.png" alt="" class="h-full w-64 animate-hover"/>
            <img src="/img/screen-2.png" alt="" class="h-full w-64 pt-20 animate-hover"/>
          </div>
        </div>

      </div>
      
    </div>

  </div>
</template>


