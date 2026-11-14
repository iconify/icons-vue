<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a1p54ripv"/><path class="yoz2ntbog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crystal-ball" /></template>
<style>
.a1p54ripv {
  d: path("M7.5 16a7.5 7.5 0 1 1 9 0m-9 0l-3 5h15l-3-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yoz2ntbog {
  d: path("M8 10a4 4 0 0 1 4-4");
}

</style>
