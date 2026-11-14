<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a_vs02bzk"/><path class="c3l4gpujl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:infographic" /></template>
<style>
.a_vs02bzk {
  d: path("M3 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.c3l4gpujl {
  d: path("M7.5 3.5V8H12m3-2.5h6m-6 5h4M3 20l5-4l5 2l8-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
