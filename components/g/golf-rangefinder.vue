<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pkag1cbnc"/><path class="z63lv2vch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-rangefinder" /></template>
<style>
.pkag1cbnc {
  d: path("M2.5 9.5h4l3-3h10a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-10l-3-3h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z63lv2vch {
  d: path("M13 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 0h.01");
}

</style>
