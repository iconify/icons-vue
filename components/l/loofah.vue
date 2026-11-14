<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qo-wxdh9d"/><path class="xabw3fv9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loofah" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qo-wxdh9d {
  d: path("M4 13.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

.xabw3fv9h {
  d: path("M10 5.75C9 2 15 2 14 5.75M8 10.5q2-1.5 4 0t4 0m-9 3q2.5-1.5 5 0t5 0m-9 3q2-1.5 4 0t4 0");
}

</style>
