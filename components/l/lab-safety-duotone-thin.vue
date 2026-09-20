<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_w2e0bxp"/><path class="a0f0f2w0j"/><path class="qk-gt2bvd"/><path class="gwnaabclj"/><path class="me177l4bh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lab-safety-duotone-thin" /></template>
<style>
.a0f0f2w0j {
  fill: currentColor;
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gwnaabclj {
  d: path("M12 9v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_w2e0bxp {
  fill: currentColor;
  d: path("m12 3 9 16H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.me177l4bh {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qk-gt2bvd {
  d: path("m12 3 9 16H3Z");
}

</style>
