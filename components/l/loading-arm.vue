<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d_9un9fgp"/><path class="cpx5bhaer"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loading-arm" /></template>
<style>
.cpx5bhaer {
  d: path("m7.5 7l6-3.5l5.5 8V15m-.079 0h.158a1.5 1.5 0 0 1 1.455 1.864l-.291 1.166A1.28 1.28 0 0 1 19 19a1.28 1.28 0 0 1-1.243-.97l-.291-1.166A1.5 1.5 0 0 1 18.921 15");
}

.d_9un9fgp {
  d: path("M3 21.5h9M7.5 7zA1.5 1.5 0 0 1 9 8.5V20a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 6 20V8.5A1.5 1.5 0 0 1 7.5 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
