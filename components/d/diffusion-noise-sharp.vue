<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="w_-3krb5s"/><path class="yd_r2fxqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diffusion-noise-sharp" /></template>
<style>
.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w_-3krb5s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.5 4.5h.01m3.74-1h.01M5 8.5h.01M9 7.25h.01m-5.76 5h.01M7 12h.01m-2.26 4.25h.01m3.99.5h.01m-5.26 3.5h.01m3.74 0h.01m3.74.25h.01M11 3.5h.01");
}

.yd_r2fxqs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.75 6.75Q16.38 11.37 21 12q-4.62.63-5.25 5.25q-.63-4.62-5.25-5.25q4.62-.63 5.25-5.25Z");
}

</style>
