<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="pyjl6mbru"/><path class="z81zjju8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camera-strap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pyjl6mbru {
  width: 16px;
  height: 11px;
  x: 4px;
  y: 9px;
  rx: 2px;
}

.z81zjju8n {
  d: path("M15 14.5a3 3 0 1 1-6 0a3 3 0 1 1 6 0M6.5 9L9 3.75h6L17.5 9");
}

</style>
