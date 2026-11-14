<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aq2i5ccus"/><path class="ima6n9biw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:freshness-check" /></template>
<style>
.aq2i5ccus {
  d: path("M4 20C4 11 9.5 4 20 4c0 10.5-7 16-16 16Z");
}

.ima6n9biw {
  d: path("M8.5 12.5L11 15l4.5-5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
