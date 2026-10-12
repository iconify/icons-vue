<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dv9_j7_bz"/><rect class="rob4yksmo"/><path class="ce9mhcc6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-sanitizer" /></template>
<style>
.ce9mhcc6o {
  d: path("M7.75 7.25v-3.5H12m5.75 8q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5");
}

.dv9_j7_bz {
  width: 10px;
  height: 11px;
  x: 2.75px;
  y: 10.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rob4yksmo {
  width: 4.5px;
  height: 3px;
  x: 5.5px;
  y: 7.25px;
  rx: 0.75px;
}

</style>
