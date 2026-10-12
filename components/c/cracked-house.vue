<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n8choyb6m"/><path class="ckqz40b-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cracked-house" /></template>
<style>
.ckqz40b-o {
  d: path("m14 4.68l-3 4.57l3 3l-2.75 4l1.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n8choyb6m {
  d: path("m12.38 3.32l8.49 7.11q.38.32-.12.32h-1q-.5 0-.5.5v9.5q0 .5-.5.5H5.25q-.5 0-.5-.5v-9.5q0-.5-.5-.5h-1q-.5 0-.12-.32l8.49-7.11q.38-.32.76 0");
}

</style>
