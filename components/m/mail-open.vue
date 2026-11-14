<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i0up1jxkc"/><path class="dlpk0pdin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mail-open" /></template>
<style>
.dlpk0pdin {
  d: path("m3.5 10.5l8.5 5l8.5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0up1jxkc {
  d: path("m3 10l9-6l9 6v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
