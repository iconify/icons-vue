<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l3a9-l0qh"/><path class="k65k4g4jh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grid-tile-map" /></template>
<style>
.k65k4g4jh {
  fill: currentColor;
  d: path("M13.5 13.5h7v7h-7Z");
}

.l3a9-l0qh {
  d: path("M3.5 3.5h7v7h-7Zm10 0h7v7h-7Zm-10 10h7v7h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
