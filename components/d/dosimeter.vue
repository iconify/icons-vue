<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nhdhxxbeu"/><path class="tyzfstkvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dosimeter" /></template>
<style>
.nhdhxxbeu {
  d: path("M5 5h14v16.5H5Zm4.5 0V2.5h5V5");
}

.tyzfstkvr {
  d: path("M7.5 15.5a4.5 4.5 0 0 1 9 0m-4.5 0l2.5-3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
