<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h5kqv07ib"/><circle class="c70vv4bjr"/><path class="r7slpvz7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buoy-marine" /></template>
<style>
.c70vv4bjr {
  cx: 12px;
  cy: 4.75px;
  r: 1.75px;
}

.h5kqv07ib {
  d: path("m6.46 16.53l1.83-6.31q.21-.72.96-.72h5.5q.75 0 .96.72l1.83 6.31q.21.72-.54.72H7q-.75 0-.54-.72m.94-3.03h9.2m-6.85-4l1.25-3m3.25 3L13 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r7slpvz7b {
  d: path("M2.75 20.75C4 20.75 4 20 5.25 20s1.25.75 2.5.75S9 20 10.25 20s1.25.75 2.5.75S14 20 15.25 20s1.25.75 2.5.75S19 20 20.25 20");
}

</style>
