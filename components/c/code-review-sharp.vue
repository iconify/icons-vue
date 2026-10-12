<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qe3ql531d"/><path class="eecrw4bqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:code-review-sharp" /></template>
<style>
.eecrw4bqw {
  d: path("m9.75 8.25l-2.25 2.5l2.25 2.5m4.5-5l2.25 2.5l-2.25 2.5");
}

.qe3ql531d {
  d: path("M5.25 3.75h16v14h-11l-3.5 2.9l-1.299 1.164l.049-1.744v-2.32l-2.764.278l.014-2.778V3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
