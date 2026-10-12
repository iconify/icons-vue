<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mz3y6c41u"/><path class="yj7s5unvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:interview-questions" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mz3y6c41u {
  cx: 7.5px;
  cy: 9.5px;
  r: 3px;
}

.yj7s5unvw {
  d: path("M3.5 20.25h8a.75.75 0 0 0 .75-.75c0-2.9-2.25-5-4.75-5s-4.75 2.1-4.75 5a.75.75 0 0 0 .75.75m11.75-17.5h4a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H16.5l-2.5 2V9.7a2 2 0 0 1-1.75-1.95v-3a2 2 0 0 1 2-2Z");
}

</style>
