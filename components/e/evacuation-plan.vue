<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m1f46jbfm"/><path class="a7290z_hy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:evacuation-plan" /></template>
<style>
.a7290z_hy {
  d: path("m3.5 11l2-1.75L8 9l2.75 2.25M16.25 9L19 12l-2.75 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1f46jbfm {
  d: path("M15.25 2.5H20a1.75 1.75 0 0 1 1.75 1.75v15.5A1.75 1.75 0 0 1 20 21.5h-4.75a1.75 1.75 0 0 1-1.75-1.75V4.25a1.75 1.75 0 0 1 1.75-1.75M7 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8 9l-1.5 5l3 3v4m-3-7l-1.75 4l-2.25 1");
}

</style>
