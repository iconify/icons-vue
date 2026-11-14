<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3w0lfb8x"/><path class="wdvbn4b7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cpu-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3w0lfb8x {
  d: path("M9 5.5h6A3.5 3.5 0 0 1 18.5 9v6a3.5 3.5 0 0 1-3.5 3.5H9A3.5 3.5 0 0 1 5.5 15V9A3.5 3.5 0 0 1 9 5.5");
}

.wdvbn4b7e {
  d: path("m9 12.25l2 2l4-4M9.5 2.5v3m5-3v3m-5 13v3m5-3v3m-12-12h3m-3 5h3m13-5h3m-3 5h3");
}

</style>
