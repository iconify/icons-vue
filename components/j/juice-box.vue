<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="znjjtbb0f"/><path class="faj3yn61r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:juice-box" /></template>
<style>
.faj3yn61r {
  d: path("M11 11.25c1.5 2 2.75 3.5 2.75 4.75a2.75 2.75 0 0 1-5.5 0c0-1.25 1.25-2.75 2.75-4.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znjjtbb0f {
  d: path("M5.5 7.5h11v14h-11Zm8.5 0V4l4.5-1.5");
}

</style>
