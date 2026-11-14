<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zjnb-gbbu"/><path class="cmmoq4bgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cochlear-implant" /></template>
<style>
.cmmoq4bgd {
  d: path("M6.75 9c0-1.75 1.25-3 3-3s2.75 1.25 2.75 2.75S11.25 11 10.25 12m8.5-6h.01m-.01 2.75c0 2.75-1.25 4.75-3 6.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zjnb-gbbu {
  d: path("M3.75 9c0-3.5 2.5-6 6-6c3.25 0 5.5 2.5 5.5 5.75c0 2.75-1.5 4-2.75 5.25s-1.25 2.5-1.75 4.5c-.5 1.75-2 2.5-3.5 2.5c-2 0-3.5-1.5-3.5-3.5M16 6a2.75 2.75 0 1 0 5.5 0A2.75 2.75 0 1 0 16 6Z");
}

</style>
