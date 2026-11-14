<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sg7at7uic"/><path class="ae9j4hb0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kid-raising-hand" /></template>
<style>
.ae9j4hb0i {
  d: path("M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sg7at7uic {
  d: path("M19 4.5L16.25 16C15 14.75 13 14 10.5 14C6.25 14 3 16.25 3 19.5v1h15c0-2-.5-3.5-1.75-4.5");
}

</style>
