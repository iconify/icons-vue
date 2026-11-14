<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ln241o5we"/><path class="un63m5bhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:export-asset" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ln241o5we {
  d: path("M8 9.5a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-8a2 2 0 0 0-2-2");
}

.un63m5bhg {
  d: path("m13.061 3.561l2.217 2.217a.57.57 0 0 1-.403.972A1.375 1.375 0 0 0 13.5 8.125V15a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5V8.125A1.375 1.375 0 0 0 9.125 6.75a.57.57 0 0 1-.403-.972l2.217-2.217a1.5 1.5 0 0 1 2.122 0");
}

</style>
