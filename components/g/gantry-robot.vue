<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m4scshb7d"/><path class="orp5clbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gantry-robot" /></template>
<style>
.m4scshb7d {
  d: path("M4 21V4h16v17");
}

.orp5clbmm {
  d: path("M9.5 4h5v3.5h-5ZM12 7.5v5m-3 4v-4h6v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
