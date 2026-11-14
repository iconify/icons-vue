<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yuski1b9b"/><path class="nov6dvb7n"/><path class="g1z3xujdd"/><path class="ai6004e4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:code-compare" /></template>
<style>
.ai6004e4w {
  d: path("m12.75 6l-2 2l2 2");
}

.g1z3xujdd {
  d: path("m11.25 14l2 2l-2 2M18 15.75V11a3 3 0 0 0-3-3h-4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nov6dvb7n {
  d: path("M6 8.25V13a3 3 0 0 0 3 3h4.25");
}

.yuski1b9b {
  d: path("M3.75 6a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m12 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
