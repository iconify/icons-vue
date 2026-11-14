<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k2v8kx6pu"/><path class="wpghg4bsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:farmhouse" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2v8kx6pu {
  d: path("m2.964 10.497l4.25-4.604a1.75 1.75 0 0 1 2.572 0l4.25 4.604a1.75 1.75 0 0 1 .464 1.187v8.066a1.75 1.75 0 0 1-1.75 1.75h-8.5a1.75 1.75 0 0 1-1.75-1.75v-8.066a1.75 1.75 0 0 1 .464-1.187");
}

.wpghg4bsg {
  d: path("M14.5 21.5V7a3.5 3.5 0 0 1 7 0v14.5Zm-8 0V17h4v4.5m4-10.5h7");
}

</style>
