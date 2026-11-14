<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jmsbkogou"/><path class="kju49ybrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:free-throw" /></template>
<style>
.jmsbkogou {
  d: path("M7.5 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm-3 7.25h15m-13 0l2 7.25h7l2-7.25M7.5 7h9");
}

.kju49ybrj {
  d: path("M9.5 3.25q2.5 3.75 0 7.5m5-7.5q-2.5 3.75 0 7.5m-6 10.75l3.5-7.25l3.5 7.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
