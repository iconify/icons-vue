<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e4k0yvb4z"/><path class="a_quq5bpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-key" /></template>
<style>
.a_quq5bpv {
  d: path("M5.25 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.e4k0yvb4z {
  d: path("M7.25 7zA4.75 4.75 0 0 1 12 11.75v.5A4.75 4.75 0 0 1 7.25 17a4.75 4.75 0 0 1-4.75-4.75v-.5A4.75 4.75 0 0 1 7.25 7M12 10h8l1.5 1.5v2h-3v2h-3v-2H12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
