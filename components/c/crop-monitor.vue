<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qerrjoyja"/><path class="e-menhr0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crop-monitor" /></template>
<style>
.e-menhr0w {
  d: path("M12 11c0-1.68-1.12-2.57-3-2.5c.07 1.5 1.2 2.4 3 2.5m0-1c0-1.8 1.13-3.15 3-3.25c-.07 1.9-1.2 3.25-3 3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qerrjoyja {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V7A3.5 3.5 0 0 1 6 3.5m6 13v4m-4 0h8m-4-7.25V10");
}

</style>
