<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bsc8bt6mm"/><path class="dpvi79uvs"/><path class="p4gggz_ng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-sleet-sharp-two-tone" /></template>
<style>
.bsc8bt6mm {
  stroke-opacity: 0.4;
  d: path("M4.5 16.753L4 16.464C2.762 15.75 2 14.429 2 13C2 10.791 3.791 9 6 9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9C20.209 9 22 10.791 22 13C22 14.429 21.238 15.75 20 16.464L19.5 16.753");
}

.dpvi79uvs {
  fill: currentColor;
  d: path("M13 19C13 19.552 12.552 20 12 20C11.448 20 11 19.552 11 19C11 18.448 11.448 18 12 18C12.552 18 13 18.448 13 19Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4gggz_ng {
  d: path("M8 16V22M16 16V22");
}

</style>
