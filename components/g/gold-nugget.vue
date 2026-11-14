<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e56d5rtnr"/><path class="gj0cjcbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gold-nugget" /></template>
<style>
.e56d5rtnr {
  d: path("m3.64 13.995l2.497-3.924a1.75 1.75 0 0 1 1.016-.749l4.311-1.176a1.75 1.75 0 0 1 1.058.044l4.419 1.607a1.75 1.75 0 0 1 .878.705l2.6 4.086a1.75 1.75 0 0 1 .025 1.839L18.51 19.65a1.75 1.75 0 0 1-1.501.85H7.891a1.75 1.75 0 0 1-1.415-.721l-2.775-3.815a1.75 1.75 0 0 1-.061-1.969");
}

.gj0cjcbut {
  d: path("m6.5 9.5l4 4.5l7-4m-7 4l2 6.5m6-18.25q0 2.5 2.5 2.5q-2.5 0-2.5 2.5q0-2.5-2.5-2.5q2.5 0 2.5-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
