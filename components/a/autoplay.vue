<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d5cgy1yrk"/><path class="jy3z01sga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:autoplay" /></template>
<style>
.d5cgy1yrk {
  d: path("M18.25 5.75a8.75 8.75 0 1 1-12.5 0");
}

.jy3z01sga {
  d: path("M3.25 5.75h2.5v2.5M9.5 8l6.5 4l-6.5 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
