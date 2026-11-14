<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vyk2jgbrd"/><path class="e8l5aqbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:defect-part" /></template>
<style>
.e8l5aqbax {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5l-1.75 3.25l3.5 3.25L12 21.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vyk2jgbrd {
  d: path("M12 2.5L20.5 7v10L12 21.5L3.5 17V7Z");
}

</style>
