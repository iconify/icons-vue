<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i5ulkkbpc"/><path class="rsmc4uepx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-pump" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5ulkkbpc {
  d: path("M5.125 4.5h13.75A2.625 2.625 0 0 1 21.5 7.125v8.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 15.875v-8.75A2.625 2.625 0 0 1 5.125 4.5m.375 14V21m13-2.5V21");
}

.rsmc4uepx {
  d: path("M5 11.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m0 0h9M9.5 7v9m7.25-7.5H19m-2.25 3H19m-2.25 3H19");
}

</style>
