<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vxh-ftnjv"/><path class="dwwgy-e6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:corner-down-left" /></template>
<style>
.dwwgy-e6i {
  d: path("m9.5 9.5l-5 5l5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vxh-ftnjv {
  d: path("M19.5 4.5V11a3.5 3.5 0 0 1-3.5 3.5H4.5");
}

</style>
