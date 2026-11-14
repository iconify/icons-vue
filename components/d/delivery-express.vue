<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="urn2n47on"/><path class="vfoa9ubnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-express" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.urn2n47on {
  d: path("m15 4.75l6.25 3.5v7.5L15 19.25l-6.25-3.5v-7.5Z");
}

.vfoa9ubnw {
  d: path("M8.75 8.25L15 12l6.25-3.75M15 12v7.25M3.5 8.5H6M2.5 12H6m-2.5 3.5H6");
}

</style>
