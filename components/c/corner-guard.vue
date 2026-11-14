<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tj57lu47i"/><path class="heo37re6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corner-guard" /></template>
<style>
.heo37re6p {
  d: path("M13 7V2.5H7.5a5 5 0 0 0-5 5V13H7");
}

.tj57lu47i {
  d: path("M21.5 7h-12A2.5 2.5 0 0 0 7 9.5v12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
