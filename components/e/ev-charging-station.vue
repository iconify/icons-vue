<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxwbfbb6h"/><path class="toscoiuso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ev-charging-station" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.toscoiuso {
  d: path("m10 5.5l-2.5 5h3l-2.5 5");
}

.yxwbfbb6h {
  d: path("M7.5 2.5h3A3.5 3.5 0 0 1 14 6v12a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 4 18V6a3.5 3.5 0 0 1 3.5-3.5M14 8h2q1.5 0 1.5 1.5v7q0 2 1.75 2t1.75-2V7l-1.5-1.5");
}

</style>
