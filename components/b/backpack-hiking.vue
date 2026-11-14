<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cdxsy_2ye"/><path class="l3p54zhkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backpack-hiking" /></template>
<style>
.cdxsy_2ye {
  d: path("M6.5 16V8q0-5 5.5-5t5.5 5v8M4 16h14.5a2.5 2.5 0 0 1 0 5H4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3p54zhkz {
  d: path("M2.5 18.5a1.5 2.5 0 1 0 3 0a1.5 2.5 0 1 0-3 0m4-10q5.5 2 11 0M9 16v5m6-5v5");
}

</style>
