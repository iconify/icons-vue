<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2zbypb8m"/><path class="yb5-eqq7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bouncy-castle" /></template>
<style>
.d2zbypb8m {
  d: path("M4.5 18V7A2.25 2.25 0 0 1 9 7v3q1.5-2 3 0q1.5-2 3 0V7a2.25 2.25 0 0 1 4.5 0v11m-17 0h19v3.5h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yb5-eqq7q {
  d: path("M10 18v-3a2 2 0 0 1 4 0v3");
}

</style>
