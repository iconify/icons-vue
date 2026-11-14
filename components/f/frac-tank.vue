<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fz9337bep"/><path class="uv5ke20gu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frac-tank" /></template>
<style>
.fz9337bep {
  d: path("M7.25 6h9.5a4.75 4.75 0 0 1 4.75 4.75a4.75 4.75 0 0 1-4.75 4.75h-9.5a4.75 4.75 0 0 1-4.75-4.75A4.75 4.75 0 0 1 7.25 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uv5ke20gu {
  d: path("M5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M12 6V3m-1.5 0h3");
}

</style>
