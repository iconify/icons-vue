<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yz9qscb4w"/><path class="eze5h4biv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-whistle" /></template>
<style>
.eze5h4biv {
  d: path("M2 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm13-2a4 4 0 0 1 4 4m-4-7a7 7 0 0 1 7 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz9qscb4w {
  d: path("M2.5 11.5H12A4.5 4.5 0 1 1 7.5 16v-1h-5Z");
}

</style>
