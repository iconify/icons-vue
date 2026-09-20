<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhy5nnbig"/><path class="dsws0rb8d"/><path class="yy7evi_9s"/><path class="o_ssmh9ez"/><path class="czq2o7bav"/><path class="uv-0dacjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:living-cell-duotone-thin" /></template>
<style>
.czq2o7bav {
  d: path("M11 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.dsws0rb8d {
  fill: currentColor;
  d: path("M11 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.uv-0dacjj {
  d: path("M7 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yy7evi_9s {
  fill: currentColor;
  d: path("M7 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zhy5nnbig {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
