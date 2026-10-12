<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qkz0k2btf"/><path class="cfwwefjkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bomber-jacket" /></template>
<style>
.cfwwefjkb {
  d: path("m9.75 3.5l2.25 5l2.25-5M12 8.5v12.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qkz0k2btf {
  d: path("M9.75 3.25h4.5l4.5 1q2.5.55 2.5 3.25v11.25a.75.75 0 0 1-.75.75H19a.75.75 0 0 1-.75-.75V9a1.5 1.5 0 0 0-3 0v11a.75.75 0 0 1-.75.75h-5a.75.75 0 0 1-.75-.75V9a1.5 1.5 0 0 0-3 0v9.75a.75.75 0 0 1-.75.75H3.5a.75.75 0 0 1-.75-.75V7.5q0-2.7 2.5-3.25Z");
}

</style>
