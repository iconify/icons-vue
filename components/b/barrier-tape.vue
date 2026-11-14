<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wzq03qhpx"/><path class="yo-318cjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barrier-tape" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wzq03qhpx {
  d: path("M4 4.5V20M20 4.5V20M2.5 20h3m13 0h3M4 6.5q8 7 16 0");
}

.yo-318cjj {
  d: path("M4 10.5q8 7 16 0m-9.5-.5l-2 3.25m7.5-4l-2 4.5");
}

</style>
