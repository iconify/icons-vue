<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uaztn_b2j"/><path class="yu1sxcvkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barn-owl" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uaztn_b2j {
  d: path("M12 6C9 2.5 3.5 3.5 3.5 9.5C3.5 15 8 19 12 21c4-2 8.5-6 8.5-11.5c0-6-5.5-7-8.5-3.5");
}

.yu1sxcvkg {
  d: path("M6.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.5 3V16");
}

</style>
