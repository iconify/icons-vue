<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h21n0dbod"/><path class="ediyfmbyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crank-radio" /></template>
<style>
.ediyfmbyd {
  d: path("M7.5 14a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 0h6");
}

.h21n0dbod {
  d: path("M4 8h16v12H4Zm12 0l3.5-5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
