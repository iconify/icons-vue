<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c1gtl6z7a"/><path class="mpuc5nnlb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:football-kids" /></template>
<style>
.c1gtl6z7a {
  d: path("M3 11a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm-.5 9.5h19");
}

.mpuc5nnlb {
  d: path("m9.5 8.25l2.75 2l-1 3h-3.5l-1-3Zm0 0V4.5m2.75 5.75l3.5-1m-4.5 4l2 3m-5.5-3l-2 3m1-6l-3.5-1M16.5 20.5l2.25-6.5L21 20.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
