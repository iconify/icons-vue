<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c25lkgbgb"/><path class="ca5b8gbur"/><path class="kvdjm4bsr"/><path class="rkzreok7b"/><path class="rwnv8qbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-round-minimalistic-broken" /></template>
<style>
.c25lkgbgb {
  d: path("M8 11V13");
}

.ca5b8gbur {
  d: path("M16 11V13");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvdjm4bsr {
  d: path("M9.1709 4C9.58273 2.83481 10.694 2 12.0002 2C13.3064 2 14.4177 2.83481 14.8295 4");
}

.rkzreok7b {
  d: path("M22 14C22 10.2288 22 8.34315 20.8284 7.17157C20.0781 6.42122 19.0348 6.15144 17.3909 6.05445C16.468 6 15.3559 6 14 6H10C8.64413 6 7.53199 6 6.60915 6.05445C4.96519 6.15144 3.92193 6.42122 3.17157 7.17157C2 8.34315 2 10.2288 2 14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C21.4816 20.1752 21.7706 19.3001 21.8985 18");
}

.rwnv8qbti {
  d: path("M21.6764 8.70569L21.5959 8.75806C18.6394 10.6798 17.1334 11.6587 15.5611 12.1472C13.2421 12.8677 10.7592 12.8677 8.44021 12.1472C6.85371 11.6543 5.3321 10.6716 2.32227 8.71517");
}

</style>
