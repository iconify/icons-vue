<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0i1yybpz"/><path class="m_zuvmbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hiit-workout" /></template>
<style>
.a0i1yybpz {
  d: path("M3.75 13a8.25 8.25 0 1 0 16.5 0a8.25 8.25 0 1 0-16.5 0M10 2.75h4m-2 0v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_zuvmbsf {
  d: path("m12.95 8.4l-3.9 5.2q-.3.4.2.4h2.25q.5 0 .35.48l-.95 3.04q-.15.48.15.08l3.9-5.2q.3-.4-.2-.4H12.5q-.5 0-.35-.48l.95-3.04q.15-.48-.15-.08");
}

</style>
