<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="qpbfohcpa"/><path class="r31ycqkub"/><path class="f6_7j78_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:architecture-decision" /></template>
<style>
.f6_7j78_y {
  d: path("M11 10.5v3.25L8.25 17M11 13.75L13.75 17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qpbfohcpa {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4");
}

.r31ycqkub {
  fill: currentColor;
  d: path("M10 10.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0M7.25 17a1 1 0 1 0 2 0a1 1 0 1 0-2 0m5.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
