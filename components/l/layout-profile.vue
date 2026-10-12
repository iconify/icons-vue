<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g6ctus9qt"/><circle class="d4r-zbeif"/><path class="rlgfn7b0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layout-profile" /></template>
<style>
.d4r-zbeif {
  cx: 12px;
  cy: 8px;
  r: 2.25px;
}

.g6ctus9qt {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rlgfn7b0e {
  d: path("M8 15c.8-1.5 2.3-2.25 4-2.25s3.2.75 4 2.25m-8 3.25h8");
}

</style>
