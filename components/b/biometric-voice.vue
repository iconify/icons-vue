<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9b0w8b8t"/><path class="us5pxeagv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biometric-voice" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9b0w8b8t {
  d: path("M12 3za2 2 0 0 1 2 2v5a2 2 0 0 1-2 2a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2");
}

.us5pxeagv {
  d: path("M7 10a5 5 0 0 0 10 0m-5 5v5m-3 0h6M4.5 6.5q-2 3.5 0 7m15-7q2 3.5 0 7");
}

</style>
