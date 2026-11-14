<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uz8a73byf"/><path class="zmn9lmzwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fix-leak" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uz8a73byf {
  d: path("M2.5 7H12a5 5 0 0 1 5 5v1.5");
}

.zmn9lmzwe {
  d: path("M6.5 4.5h3v5h-3Zm8 9h5m-2.5 3s-2 2.25-2 3.5a2 2 0 0 0 4 0c0-1.25-2-3.5-2-3.5Z");
}

</style>
