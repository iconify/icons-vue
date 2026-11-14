<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jga5vkbqn"/><path class="rcz-qkbkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:feature-flag-service" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jga5vkbqn {
  d: path("M5.25 4h9.441A1.548 1.548 0 0 1 16 6.375l-.91 1.441a1.75 1.75 0 0 0 0 1.868l.91 1.441a1.548 1.548 0 0 1-1.309 2.375H5.25a1.75 1.75 0 0 1-1.75-1.75v-6A1.75 1.75 0 0 1 5.25 4M3.5 3v18m13-4.5h3A2.5 2.5 0 0 1 22 19a2.5 2.5 0 0 1-2.5 2.5h-3A2.5 2.5 0 0 1 14 19a2.5 2.5 0 0 1 2.5-2.5");
}

.rcz-qkbkc {
  d: path("M18.5 19a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
