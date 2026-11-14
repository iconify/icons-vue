<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8hq-0bpb"/><path class="z7ik0obsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:low-fuel" /></template>
<style>
.d8hq-0bpb {
  d: path("M3.5 20.5v-15a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v15Zm-1 0h13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7ik0obsk {
  d: path("M8.25 6.5h1.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 6.5 8.75v-.5A1.75 1.75 0 0 1 8.25 6.5M14.5 11h1.25a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 0 3 0V9L18 6.75");
}

</style>
