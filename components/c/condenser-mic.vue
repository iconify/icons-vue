<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x49qblb_c"/><path class="m1l7gp4zs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:condenser-mic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1l7gp4zs {
  d: path("M4.5 9v1.5a7.5 7.5 0 0 0 15 0V9m-12-.25h9");
}

.x49qblb_c {
  d: path("M12 2.5zA4.5 4.5 0 0 1 16.5 7v3.5A4.5 4.5 0 0 1 12 15a4.5 4.5 0 0 1-4.5-4.5V7A4.5 4.5 0 0 1 12 2.5m0 16v3m-3.5 0h7");
}

</style>
