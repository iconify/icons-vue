<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hf1-ywb7x"/><path class="u_9k4bc-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bull-head" /></template>
<style>
.hf1-ywb7x {
  d: path("M6.5 6.5h11L16 14c-.5 2-2 3-4 3s-3.5-1-4-3Zm0 0c-3 0-4-1.5-4-4m15 4c3 0 4-1.5 4-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u_9k4bc-c {
  d: path("M10 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.25-9h.01m4.49 0h.01");
}

</style>
