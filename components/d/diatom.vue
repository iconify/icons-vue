<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t9ekovb2i"/><path class="u-s9lqw1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diatom" /></template>
<style>
.t9ekovb2i {
  d: path("M4 12a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

.u-s9lqw1s {
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm9.25-5.75L20 4M6.25 6.25L4 4m13.75 13.75L20 20M6.25 17.75L4 20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
