<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="smd5nc9bz"/><path class="kox7k4x-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boxing-workout" /></template>
<style>
.kox7k4x-v {
  d: path("M6 12h3.5a2 2 0 0 1 0 4H7m0 3h9.5v2.5H7Z");
}

.smd5nc9bz {
  d: path("M6 11a6 6 0 0 1 12-1.5V13a6 6 0 0 1-6 6H9a3 3 0 0 1-3-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
