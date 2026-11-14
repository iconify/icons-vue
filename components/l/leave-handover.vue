<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p_-6ywc6j"/><path class="was4qfbnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leave-handover" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_-6ywc6j {
  d: path("M9 2.5h6A1.5 1.5 0 0 1 16.5 4v4l1 1.5v10a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2v-10l1-1.5V4A1.5 1.5 0 0 1 9 2.5");
}

.was4qfbnx {
  d: path("M10.25 5.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3.5 0h2.75M9.25 12.5h5.5m-1.5-1.5l1.5 1.5l-1.5 1.5m1.5 3.5h-5.5m1.5-1.5l-1.5 1.5l1.5 1.5");
}

</style>
