<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fed2k6bxs"/><path class="l97nezbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gravel-trap" /></template>
<style>
.fed2k6bxs {
  d: path("M2.5 9c5.5 0 7-3 7-6.5M2.5 14c8 0 12-5 12-11.5");
}

.l97nezbrg {
  fill: currentColor;
  d: path("M21.5 5v16.5H5c7 0 16.5-8.5 16.5-16.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
