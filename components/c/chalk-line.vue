<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="setfh3lep"/><path class="m0dvmebba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chalk-line" /></template>
<style>
.m0dvmebba {
  d: path("M7 14.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.setfh3lep {
  d: path("M3 14.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm1.5 4l-2 2M8.5 9l13-4m0-2.5V10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
