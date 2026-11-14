<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h1xvpfiwc"/><path class="wt_u87cfg"/><path class="jio7b861e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lavender" /></template>
<style>
.h1xvpfiwc {
  d: path("M10 4.25a2 1.75 0 1 0 4 0a2 1.75 0 1 0-4 0Z");
}

.jio7b861e {
  d: path("M10 11.25a2 1.75 0 1 0 4 0a2 1.75 0 1 0-4 0ZM12 13v8m0-2.5q-4.5-1-5.5-6m5.5 6q4.5-1 5.5-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wt_u87cfg {
  d: path("M10 7.75a2 1.75 0 1 0 4 0a2 1.75 0 1 0-4 0Z");
}

</style>
