<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xb280sbwz"/><path class="qoupp8b_p"/><path class="ez39r6bms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:aisle-seat-duotone-thin" /></template>
<style>
.ez39r6bms {
  d: path("M17 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qoupp8b_p {
  d: path("M4 4v16h8V4Z");
}

.xb280sbwz {
  fill: currentColor;
  d: path("M4 4v16h8V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
