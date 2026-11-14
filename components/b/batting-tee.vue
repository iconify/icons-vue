<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fykya3wqx"/><path class="v51uvrb0f"/><path class="i5_3kl_9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:batting-tee" /></template>
<style>
.fykya3wqx {
  d: path("M7.5 6.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5_3kl_9y {
  d: path("M6 18.5h12a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20A1.5 1.5 0 0 1 6 18.5M9 3.25q1.5 3.25 0 6.5m6-6.5q-1.5 3.25 0 6.5");
}

.v51uvrb0f {
  d: path("M12 11za1.476 1.476 0 0 1 1.455 1.233l.754 4.52a1.5 1.5 0 0 1-1.48 1.747h-1.458a1.5 1.5 0 0 1-1.48-1.747l.754-4.52A1.476 1.476 0 0 1 12 11");
}

</style>
