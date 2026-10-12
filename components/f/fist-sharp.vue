<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="be0lrgb8d"/><path class="miw2dibhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fist-sharp" /></template>
<style>
.be0lrgb8d {
  d: path("M5.25 14V7.75h3v1.5V6.5h3v1.75v-1.5h3V9V7.5h3v7l-.013 2.395L15 17.75v3.5H9v-3.5H5.25zm3-4.75V10m3-2v1.5m3-1.25V9.5");
}

.miw2dibhh {
  d: path("m8.8 11.81l4.5-.6a1.5 1.5 0 0 1 .4 2.98l-4.5.6a1.5 1.5 0 0 1-.4-2.98Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
