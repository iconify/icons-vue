<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j5yixmbie"/><path class="r4zu_6b1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ballot-scanner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5yixmbie {
  d: path("M6 12h12a3.5 3.5 0 0 1 3.5 3.5v.5a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16v-.5A3.5 3.5 0 0 1 6 12m1.5 0V4A1.5 1.5 0 0 1 9 2.5h6A1.5 1.5 0 0 1 16.5 4v8");
}

.r4zu_6b1f {
  d: path("M10 7.5L11.5 9L14 6.5m4 9.25h.01");
}

</style>
