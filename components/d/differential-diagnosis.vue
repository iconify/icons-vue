<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lvy3hlsgp"/><path class="asi79cb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:differential-diagnosis" /></template>
<style>
.asi79cb2i {
  fill: currentColor;
  d: path("M16 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m1 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lvy3hlsgp {
  d: path("M2.5 12H9m0 0l6-6m-6 6h6.5M9 12l6 6");
}

</style>
