<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g-o--obtk"/><path class="xw6sd0bzz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:daily-mix-play" /></template>
<style>
.g-o--obtk {
  d: path("M6.5 7.5h8A3.5 3.5 0 0 1 18 11v5a3.5 3.5 0 0 1-3.5 3.5h-8A3.5 3.5 0 0 1 3 16v-5a3.5 3.5 0 0 1 3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xw6sd0bzz {
  d: path("M6.5 4.5H19a2 2 0 0 1 2 2V16m-10.256-4.218l.727.416a1.5 1.5 0 0 1 0 2.604l-.727.416A1.5 1.5 0 0 1 8.5 13.915v-.83a1.5 1.5 0 0 1 2.244-1.303");
}

</style>
