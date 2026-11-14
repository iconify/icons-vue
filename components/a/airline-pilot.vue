<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aa8i3yb1t"/><path class="o1m77pzum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:airline-pilot" /></template>
<style>
.aa8i3yb1t {
  d: path("M4.5 7c0-2.75 3.25-4.5 7.5-4.5s7.5 1.75 7.5 4.5L17 9H7ZM8 9v2a4 4 0 0 0 8 0V9M4.5 21.5c0-2.25 3.25-3.75 7.5-3.75s7.5 1.5 7.5 3.75");
}

.o1m77pzum {
  d: path("m9.5 6.25l2.5-1l2.5 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
