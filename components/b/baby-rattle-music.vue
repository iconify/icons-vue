<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ls_02nbvg"/><path class="zv60afjtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-rattle-music" /></template>
<style>
.ls_02nbvg {
  d: path("M3 8a5.5 5.5 0 1 0 11 0A5.5 5.5 0 1 0 3 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zv60afjtx {
  d: path("M8.5 13.5V16a2.75 2.75 0 0 1 0 5.5a2.75 2.75 0 0 1 0-5.5m5-.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0V4C19 5 21 5.5 21 8");
}

</style>
