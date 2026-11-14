<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uw0qvqr_x"/><path class="iywm0tbau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carbon-budget" /></template>
<style>
.iywm0tbau {
  d: path("M13.5 13.5v8a8 8 0 0 0 8-8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uw0qvqr_x {
  d: path("M10.5 10.5h8a8 8 0 1 0-8 8Z");
}

</style>
