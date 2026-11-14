<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aphvy1aeu"/><path class="mgyn15bzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:goalkeeper-dive" /></template>
<style>
.aphvy1aeu {
  d: path("m16 8l-6 4l-4.5 3.5l-2.5 4m2.5-4l2.5 4M5.5 8A1.75 1.75 0 1 0 9 8a1.75 1.75 0 1 0-3.5 0Z");
}

.mgyn15bzm {
  d: path("M15.5 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
