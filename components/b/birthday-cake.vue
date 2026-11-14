<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i98xxacgg"/><path class="odv024bxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:birthday-cake" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i98xxacgg {
  d: path("M7 11.5h10a3.5 3.5 0 0 1 3.5 3.5v2a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 17v-2A3.5 3.5 0 0 1 7 11.5");
}

.odv024bxy {
  d: path("M3.5 15q2.5 2 5 0t5 0t7 0M8 11.5V8m4 3.5V8m4 3.5V8M8 5.5h.01m3.99 0h.01m3.99 0h.01");
}

</style>
