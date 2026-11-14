<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d7g23dbma"/><path class="f2hsu34uf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:condensation" /></template>
<style>
.d7g23dbma {
  d: path("M6.455 3h11.09a1.75 1.75 0 0 1 1.739 1.943l-1.611 14.5A1.75 1.75 0 0 1 15.934 21H8.066a1.75 1.75 0 0 1-1.739-1.557l-1.611-14.5A1.75 1.75 0 0 1 6.455 3");
}

.f2hsu34uf {
  d: path("M10 7.5s-1.5 2-1.5 3a1.5 1.5 0 0 0 3 0c0-1-1.5-3-1.5-3m4 5.5s-1.5 2-1.5 3a1.5 1.5 0 0 0 3 0c0-1-1.5-3-1.5-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
