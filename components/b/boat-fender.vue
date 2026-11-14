<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="csqvb1b3h"/><path class="cqczlmqbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boat-fender" /></template>
<style>
.cqczlmqbb {
  d: path("M15 8za3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5a3.5 3.5 0 0 1-3.5-3.5v-5.5A3.5 3.5 0 0 1 15 8m0-4v4m-3.5 6.25h7");
}

.csqvb1b3h {
  d: path("M21.5 4H4c0 8 1 13 4.5 17.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
