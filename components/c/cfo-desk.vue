<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppa2yhhnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cfo-desk" /></template>
<style>
.ppa2yhhnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17h19M5.625 3.5h5.25A2.625 2.625 0 0 1 13.5 6.125v3.25A2.625 2.625 0 0 1 10.875 12h-5.25A2.625 2.625 0 0 1 3 9.375v-3.25A2.625 2.625 0 0 1 5.625 3.5m12.625 3h1A1.75 1.75 0 0 1 21 8.25v7A1.75 1.75 0 0 1 19.25 17h-1a1.75 1.75 0 0 1-1.75-1.75v-7a1.75 1.75 0 0 1 1.75-1.75m-10 5.5v5M4 17v4.5M20 17v4.5");
}

</style>
