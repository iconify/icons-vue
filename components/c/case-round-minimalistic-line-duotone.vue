<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="whvrg7cyn"/><path class="k66tt2kvs"/><path class="c25lkgbgb"/><path class="ca5b8gbur"/><path class="wcev19blf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-round-minimalistic-line-duotone" /></template>
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

.k66tt2kvs {
  d: path("M10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C22 19.6569 22 17.7712 22 14C22 10.2288 22 8.34315 20.8284 7.17157C19.6569 6 17.7712 6 14 6H10C6.22876 6 4.34315 6 3.17157 7.17157C2 8.34315 2 10.2288 2 14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22Z");
}

.wcev19blf {
  d: path("M9.1709 4C9.58273 2.83481 10.694 2 12.0002 2C13.3064 2 14.4177 2.83481 14.8295 4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.whvrg7cyn {
  d: path("M21.6764 8.70569L21.5959 8.75806C18.6394 10.6798 17.1334 11.6587 15.5611 12.1472C13.2421 12.8677 10.7592 12.8677 8.44021 12.1472C6.85371 11.6543 5.3321 10.6716 2.32227 8.71517");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
