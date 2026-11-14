<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b5nepebom"/><path class="j8olcgb-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:elastic-band-sewing" /></template>
<style>
.b5nepebom {
  d: path("M2.5 7h19v10h-19Z");
}

.j8olcgb-p {
  d: path("m5.75 14l2.5-4l2.5 4l2.5-4l2.5 4l2.5-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
