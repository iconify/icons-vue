<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ih209ibyv"/><path class="fjitr8bmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invoice-partial-payment" /></template>
<style>
.fjitr8bmp {
  fill: currentColor;
  d: path("M18.5 15.5a3 3 0 0 0 0 6Z");
}

.ih209ibyv {
  d: path("M13.007 20.495L13 20.5L10.75 19L8.5 20.5L6.25 19L4 20.5v-18h13.5v10.3M7.5 7H14m-6.5 4H12m3.5 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
