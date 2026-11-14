<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nvebvjbad"/><path class="xcgk2tifr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:astronomy-class" /></template>
<style>
.nvebvjbad {
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xcgk2tifr {
  d: path("M2.5 12a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0ZM19 5h.01M5 19h.01");
}

</style>
