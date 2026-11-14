<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dd5vjg3kk"/><path class="ux7qf3bbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:figure-eight-tracks" /></template>
<style>
.dd5vjg3kk {
  d: path("M13.313 11.73A9.2 9.2 0 0 1 12 9.5c-2.5-6-9.5-6.5-9.5 0s7 6 9.5 0s9.5-6.5 9.5 0c0 1.243-.256 2.231-.688 2.972");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux7qf3bbq {
  d: path("M15.5 13.5h2.75v2.25l2.75 1v1.75h-5.5Zm-.5 7.75h6.5");
}

</style>
