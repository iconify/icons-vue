<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zuq984b0y"/><path class="cesw22b-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-review-block" /></template>
<style>
.cesw22b-u {
  d: path("M8 7L5.75 9.5L8 12m3-5l2.25 2.5L11 12m5 1.5h3.5L22 16v3.5L19.5 22H16l-2.5-2.5V16Zm0 4.25h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zuq984b0y {
  d: path("M10.7 19H3V2.5h13v8.2");
}

</style>
