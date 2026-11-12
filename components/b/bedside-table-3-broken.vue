<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="khhypgwbg"/><path class="d2-0y-bwi"/><path class="nv6qhg7zp"/><path class="sxx_hdb0w"/><path class="gjq7b_bis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bedside-table-3-broken" /></template>
<style>
.d2-0y-bwi {
  d: path("M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 6.22876 22 10V12C22 15.7712 22 17.6569 20.8284 18.8284C19.6569 20 17.7712 20 14 20H10C6.22876 20 4.34315 20 3.17157 18.8284C2 17.6569 2 15.7712 2 12V10C2 6.22876 2 4.34315 3.17157 3.17157C4.34315 2 6.22876 2 10 2");
}

.gjq7b_bis {
  d: path("M2 11H14M18 11H22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.khhypgwbg {
  d: path("M19 22V20.5M5 22V20.5");
}

.nv6qhg7zp {
  d: path("M9 15.5H15");
}

.sxx_hdb0w {
  d: path("M9 6.5H15");
}

</style>
