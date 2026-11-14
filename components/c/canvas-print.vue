<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="losnzccmu"/><path class="fixp1ccig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:canvas-print" /></template>
<style>
.fixp1ccig {
  d: path("m6.5 14.5l3-4L12 13l1.5-1.5");
}

.losnzccmu {
  d: path("M3.5 2.5h13v16h-13Zm13 0L20 4.75v16l-3.5-2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
