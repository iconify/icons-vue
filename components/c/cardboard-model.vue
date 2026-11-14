<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwu4rtb_j"/><path class="r5e3en8-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cardboard-model" /></template>
<style>
.jwu4rtb_j {
  d: path("M3 10h13v11.5H3Zm13 0l4-3v11.5l-4 3M3 10l4-3h13");
}

.r5e3en8-p {
  d: path("M3 10V4.5L6.75 3L7 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
