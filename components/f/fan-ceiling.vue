<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sv5_a61rn"/><path class="gjzf_kbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fan-ceiling" /></template>
<style>
.gjzf_kbnd {
  d: path("M13 11.75a4 1.5 0 1 0 8 0a4 1.5 0 1 0-8 0m0 5.5a4 1.5 0 1 0 8 0a4 1.5 0 1 0-8 0m-10-5.5a4 1.5 0 1 0 8 0a4 1.5 0 1 0-8 0m0 5.5a4 1.5 0 1 0 8 0a4 1.5 0 1 0-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sv5_a61rn {
  d: path("M9.5 2.5h5m-2.5 0V12m-2.5 2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
