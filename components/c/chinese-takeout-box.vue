<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jen0ixbcl"/><path class="wf66e7b8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chinese-takeout-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jen0ixbcl {
  d: path("M7.081 9h9.838a1.75 1.75 0 0 1 1.725 2.05l-1.392 8a1.75 1.75 0 0 1-1.724 1.45H8.472a1.75 1.75 0 0 1-1.724-1.45l-1.392-8A1.75 1.75 0 0 1 7.081 9");
}

.wf66e7b8t {
  d: path("m5 9l2.5-3.5h9L19 9M8.5 5.5c0-2.75 7-2.75 7 0m-3.5 0V9");
}

</style>
