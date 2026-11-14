<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gof6h-b0r"/><path class="e4bpvo96y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:circus-ringmaster" /></template>
<style>
.e4bpvo96y {
  d: path("m12.5 6.75l.159.396a1.5 1.5 0 0 0 1.257.937l.459.042a.545.545 0 0 1 .285.973l-.371.288a1.5 1.5 0 0 0-.526 1.579l.131.481a.506.506 0 0 1-.769.554l-.293-.195a1.5 1.5 0 0 0-1.664 0l-.293.195a.506.506 0 0 1-.769-.554l.131-.481a1.5 1.5 0 0 0-.526-1.579l-.371-.288a.545.545 0 0 1 .285-.973l.459-.042a1.5 1.5 0 0 0 1.257-.937l.159-.396a.539.539 0 0 1 1 0");
}

.gof6h-b0r {
  d: path("M5.5 20V4A1.5 1.5 0 0 1 7 2.5h10A1.5 1.5 0 0 1 18.5 4v16m-16 0h19m-16-4h13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
