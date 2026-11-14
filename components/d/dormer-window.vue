<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cz-3yo7et"/><path class="g3y-ujbgh"/><path class="wi_5cwbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dormer-window" /></template>
<style>
.cz-3yo7et {
  d: path("m7.5 12.5l-5 8h19l-5-8");
}

.g3y-ujbgh {
  d: path("M7.5 17.5V9L12 4.5L16.5 9v8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wi_5cwbys {
  d: path("M10.25 10h3.5v4.5h-3.5Z");
}

</style>
