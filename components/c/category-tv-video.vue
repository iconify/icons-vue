<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pivql6y5u"/><path class="uevxkub9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-tv-video" /></template>
<style>
.pivql6y5u {
  d: path("M2 3.5h20v14H2Zm5 14l-1 3m11-3l1 3");
}

.uevxkub9s {
  d: path("M9 6.25v8.5l7.5-4.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
