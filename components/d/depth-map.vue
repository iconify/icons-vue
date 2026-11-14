<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="gqsk-mblt"/><path class="sw4w7sb0q"/><path class="x_if79bzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:depth-map" /></template>
<style>
.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.gqsk-mblt {
  d: path("M5.5 13H11v5.5H5.5Z");
}

.sw4w7sb0q {
  d: path("M8.25 13v-2.75h5.5v5.5H11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x_if79bzs {
  d: path("M11 10.25V7.5h5.5V13h-2.75");
}

</style>
