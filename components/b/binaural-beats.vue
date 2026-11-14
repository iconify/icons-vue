<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h3-063b4r"/><path class="pq3f6zbas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:binaural-beats" /></template>
<style>
.h3-063b4r {
  d: path("M4.5 13v-2a7.5 7.5 0 0 1 15 0v2");
}

.pq3f6zbas {
  d: path("M2.75 12.5h3.5V20h-3.5Zm15 0h3.5V20h-3.5ZM9 16.25q1.5-4.125 3 0t3 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
