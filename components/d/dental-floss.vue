<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ryw0yrbkl"/><path class="ez2aylb7c"/><path class="csuvz0llb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-floss" /></template>
<style>
.csuvz0llb {
  d: path("M10.5 20.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.ez2aylb7c {
  d: path("M12 5q.75 7 0 14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ryw0yrbkl {
  d: path("M3 9c0-2 1.75-2.75 3-2c1.25-.75 3 0 3 2s-.75 3.25-1 5l-.5 3L6 15l-1.5 2l-.5-3c-.25-1.75-1-3-1-5m12 0c0-2 1.75-2.75 3-2c1.25-.75 3 0 3 2s-.75 3.25-1 5l-.5 3l-1.5-2l-1.5 2l-.5-3c-.25-1.75-1-3-1-5m-4.5-5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
