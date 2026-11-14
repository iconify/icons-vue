<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l-rrlcb8w"/><path class="hq5e0hzjl"/><path class="mhrzs30pu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lens-distortion" /></template>
<style>
.hq5e0hzjl {
  d: path("M9.5 4q-1 8 0 16m5-16q1 8 0 16");
}

.l-rrlcb8w {
  d: path("M5 5q7-2.5 14 0q2.5 7 0 14q-7 2.5-14 0q-2.5-7 0-14Z");
}

.mhrzs30pu {
  d: path("M4 9.5q8-1 16 0m-16 5q8 1 16 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
