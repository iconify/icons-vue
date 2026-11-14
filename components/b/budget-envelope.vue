<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ntwy5xssp"/><path class="xk2xo0boc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:budget-envelope" /></template>
<style>
.ntwy5xssp {
  d: path("M2.5 8.5h19v12h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xk2xo0boc {
  d: path("m2.5 9l9.5 5.5L21.5 9M6 8.5v-4a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v4");
}

</style>
