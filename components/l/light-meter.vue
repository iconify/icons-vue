<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d0gw_3x8b"/><path class="p1ed09bpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:light-meter" /></template>
<style>
.d0gw_3x8b {
  d: path("M9 9.5h6a3.5 3.5 0 0 1 3.5 3.5v5a3.5 3.5 0 0 1-3.5 3.5H9A3.5 3.5 0 0 1 5.5 18v-5A3.5 3.5 0 0 1 9 9.5m.5 0a2.5 2.5 0 0 1 5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p1ed09bpy {
  d: path("M9 17.5a3 3 0 0 1 6 0m-3 0l1.25-1.75M12 2.5v1.75M7 4l1.5 1.5M17 4l-1.5 1.5");
}

</style>
