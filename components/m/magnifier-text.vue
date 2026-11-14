<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ydwudw6zd"/><path class="h9sp8cbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magnifier-text" /></template>
<style>
.h9sp8cbta {
  d: path("M8 13.5L10.5 7l2.5 6.5m-4.25-2h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydwudw6zd {
  d: path("M3.5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm12 5l5 5");
}

</style>
