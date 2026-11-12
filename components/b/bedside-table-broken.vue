<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="khhypgwbg"/><path class="png6vqdtu"/><path class="rp5yf760j"/><path class="d2-0y-bwi"/><path class="u3xw_g32v"/><path class="u-d3qccyr"/><path class="vy5waob-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bedside-table-broken" /></template>
<style>
.d2-0y-bwi {
  d: path("M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 6.22876 22 10V12C22 15.7712 22 17.6569 20.8284 18.8284C19.6569 20 17.7712 20 14 20H10C6.22876 20 4.34315 20 3.17157 18.8284C2 17.6569 2 15.7712 2 12V10C2 6.22876 2 4.34315 3.17157 3.17157C4.34315 2 6.22876 2 10 2");
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

.png6vqdtu {
  d: path("M2 14H14M18 14H22");
}

.rp5yf760j {
  d: path("M2 8H22");
}

.u-d3qccyr {
  stroke-linejoin: round;
  d: path("M12 11H12.0001");
}

.u3xw_g32v {
  stroke-linejoin: round;
  d: path("M12 5H12.0001");
}

.vy5waob-q {
  stroke-linejoin: round;
  d: path("M12 17H12.0001");
}

</style>
