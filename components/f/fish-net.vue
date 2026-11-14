<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tzdelktsm"/><path class="jgd0d3b8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-net" /></template>
<style>
.jgd0d3b8q {
  d: path("M10.5 9.5C12 7 15 6.75 16.25 9.5L18 7.75v3.5L16.25 9.5C15 12.25 12 12 10.5 9.5Z");
}

.tzdelktsm {
  d: path("M7 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm2 5l-6 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
