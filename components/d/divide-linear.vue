<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y0cxd-7om"/><path class="byh8rvbcw"/><path class="uci4f6n5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:divide-linear" /></template>
<style>
.byh8rvbcw {
  d: path("M12 6H12.0001");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uci4f6n5q {
  d: path("M12 18H12.0001");
}

.y0cxd-7om {
  d: path("M4 12H20");
}

</style>
