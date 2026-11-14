<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bx8rpubcn"/><path class="bi9vllbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:immersive-space" /></template>
<style>
.bi9vllbqn {
  d: path("M4.75 18a7.25 2.5 0 1 0 14.5 0a7.25 2.5 0 1 0-14.5 0Z");
}

.bx8rpubcn {
  d: path("M4.75 18a9.5 9.5 0 1 1 14.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
