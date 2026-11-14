<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wbd8vwb8p"/><path class="vm-ctcp0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flower-seed-packet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vm-ctcp0o {
  d: path("M12 7.5a2 2 0 0 1 3.25 1.75a2 2 0 0 1 0 4A2 2 0 0 1 12 15a2 2 0 0 1-3.25-1.75a2 2 0 0 1 0-4A2 2 0 0 1 12 7.5m0 3.75h.01M12 15v3.5");
}

.wbd8vwb8p {
  d: path("m5 4.5l1.75-2l1.75 2l1.75-2l1.75 2l1.75-2l1.75 2l1.75-2l1.75 2v15a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2Z");
}

</style>
