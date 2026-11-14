<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mk5xfob2d"/><path class="qc7mgzo5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:location-history" /></template>
<style>
.mk5xfob2d {
  d: path("M5 12a8 8 0 1 1 4 6.928");
}

.qc7mgzo5l {
  d: path("m2 9l3 3l3-3m5 7s-3.5-3-3.5-5.25a3.5 3.5 0 0 1 7 0C16.5 13 13 16 13 16Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
