<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wj96bfb1c"/><path class="fszscbbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baking-tray-cookies" /></template>
<style>
.fszscbbhq {
  d: path("M7 8.25a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0m6 0a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0M6.25 12.5a2.25 1.25 0 1 0 4.5 0a2.25 1.25 0 1 0-4.5 0m7 0a2.25 1.25 0 1 0 4.5 0a2.25 1.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wj96bfb1c {
  d: path("M5 5h14l2.5 11v2.75h-19V16ZM2.5 16h19");
}

</style>
