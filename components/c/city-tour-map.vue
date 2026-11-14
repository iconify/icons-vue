<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ycpnfrb7x"/><path class="dnwry7j7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:city-tour-map" /></template>
<style>
.dnwry7j7k {
  d: path("M5.5 9.5c4 0 .5 6 5 6H16m0 0L14 13a2.5 2.5 0 1 1 4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ycpnfrb7x {
  d: path("m2.5 6l6-2l7 2l6-2v14l-6 2l-7-2l-6 2Z");
}

</style>
