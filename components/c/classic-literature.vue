<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0twtl96g"/><path class="dkeub64dj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:classic-literature" /></template>
<style>
.dkeub64dj {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5M10.75 14c-3.25-.5-3.75-5.5-2-8.5M8 10.75l-1.25-2M9 13l-1.75-.75m6 1.75c3.25-.5 3.75-5.5 2-8.5m.75 5.25l1.25-2M15 13l1.75-.75");
}

.u0twtl96g {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
