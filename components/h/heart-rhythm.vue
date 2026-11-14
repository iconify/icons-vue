<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="txytoiu8b"/><path class="ibhwheuqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-rhythm" /></template>
<style>
.ibhwheuqd {
  fill: currentColor;
  d: path("M18 21.25s-3.5-2.25-3.5-4.5c0-1 .75-2 1.75-2c.75 0 1.5.5 1.75 1c.25-.5 1-1 1.75-1c1 0 1.75 1 1.75 2c0 2.25-3.5 4.5-3.5 4.5Z");
}

.txytoiu8b {
  d: path("M2.5 10h2L6 4l1.5 10l1-4h3L13 3l1.469 9.306m.107.005L15.5 10h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
