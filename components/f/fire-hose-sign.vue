<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="mjwhy7b6h"/><path class="pgvy_tbgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-hose-sign" /></template>
<style>
.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.mjwhy7b6h {
  d: path("M6.5 11a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.pgvy_tbgk {
  d: path("M9.5 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6 0v5.5q0 2 2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
