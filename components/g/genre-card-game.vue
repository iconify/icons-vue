<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mvxzrumbk"/><path class="pur-f5vwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genre-card-game" /></template>
<style>
.mvxzrumbk {
  d: path("M10.5 6h9v15h-9Z");
}

.pur-f5vwd {
  d: path("M10.5 18L6.75 5.5L15 3l1 3M8.5 20L3 9l4-2.5m8 4l2 3l-2 3l-2-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
