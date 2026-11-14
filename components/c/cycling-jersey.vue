<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ev55nvbtd"/><path class="fsbt4lbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cycling-jersey" /></template>
<style>
.ev55nvbtd {
  d: path("M8.5 3.5L4 5.75L2.5 11L6 12v8.5h12V12l3.5-1L20 5.75L15.5 3.5Z");
}

.fsbt4lbyy {
  d: path("M8.5 3.5L9 6h6l.5-2.5M12 6v14.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
