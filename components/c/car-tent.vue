<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pc3tomb7n"/><path class="pypz9pywd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-tent" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pc3tomb7n {
  d: path("M2.5 17v-2A1.5 1.5 0 0 1 4 13.5h2.5l2-2.5h7l2.5 2.5h2a1.5 1.5 0 0 1 1.5 1.5v2Z");
}

.pypz9pywd {
  d: path("M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8 8l4-5.5L16 8v3H8Zm0 0h8");
}

</style>
