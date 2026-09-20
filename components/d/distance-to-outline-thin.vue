<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bq0_6ubvh"/><path class="bsqy413qs"/><path class="ils7yp4cg"/><path class="yhzmxzc3v"/><path class="f77ctdb-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:distance-to-outline-thin" /></template>
<style>
.bq0_6ubvh {
  d: path("M2 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.bsqy413qs {
  d: path("M16 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.f77ctdb-m {
  d: path("M21 13.5v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.yhzmxzc3v {
  d: path("M3 13.5v5");
}

</style>
