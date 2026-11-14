<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="makvcqbia"/><path class="toiawxbkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dryer-smart" /></template>
<style>
.makvcqbia {
  d: path("M15.4 21.5H3v-19h15.5v12.4M3 7h15.5");
}

.toiawxbkk {
  d: path("M6.75 13.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm11.5 1.5q0 3.25 3.25 3.25q-3.25 0-3.25 3.25q0-3.25-3.25-3.25q3.25 0 3.25-3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
