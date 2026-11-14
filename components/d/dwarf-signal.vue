<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j48grnb1t"/><path class="jlmhchb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dwarf-signal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j48grnb1t {
  d: path("M5.5 14.5v-5a6.5 6.5 0 0 1 13 0v5Zm6.5 0V21m-4 0h8");
}

.jlmhchb-q {
  d: path("M10 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
