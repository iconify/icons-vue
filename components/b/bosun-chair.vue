<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i5glcvhqr"/><path class="smv2zl5wo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bosun-chair" /></template>
<style>
.i5glcvhqr {
  d: path("M4 21.5v-18h11v8m-4 4l4-4l4 4");
}

.smv2zl5wo {
  d: path("M10 15.5h10v3H10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
