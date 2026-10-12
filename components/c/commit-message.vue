<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="qy4e2ebar"/><path class="wmmvndbva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:commit-message" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qy4e2ebar {
  cx: 12px;
  cy: 12px;
  r: 4.25px;
}

.wmmvndbva {
  d: path("M2.75 12h3.5m11.5 0h3.5");
}

</style>
