<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="csj1iib5q"/><path class="rl0hurbau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:check-badge" /></template>
<style>
.csj1iib5q {
  d: path("m21.5 12l-2.25 3l-.5 3.75l-3.75.5l-3 2.25l-3-2.25l-3.75-.5l-.5-3.75l-2.25-3l2.25-3l.5-3.75L9 4.75l3-2.25l3 2.25l3.75.5l.5 3.75Z");
}

.rl0hurbau {
  d: path("m8.5 12l2.5 2.5l4.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
