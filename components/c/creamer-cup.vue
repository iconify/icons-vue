<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e904o1b7t"/><path class="m1csnre9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:creamer-cup" /></template>
<style>
.e904o1b7t {
  d: path("M4 8a8 2.25 0 1 0 16 0A8 2.25 0 1 0 4 8Z");
}

.m1csnre9n {
  d: path("m4 8l2.75 13h10.5L20 8M7.5 6.25l-2-3.75h3l2 3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
