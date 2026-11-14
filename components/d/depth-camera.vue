<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sxi8m7bbo"/><path class="egnoewbeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:depth-camera" /></template>
<style>
.egnoewbeg {
  d: path("M5.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm11.415-3.441a6 6 0 0 1 0 6.882m1.979-9.226a9 9 0 0 1 0 11.57");
}

.sxi8m7bbo {
  d: path("M2.5 6.5h11v11h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
