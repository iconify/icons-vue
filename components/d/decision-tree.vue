<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eg2jk9bwe"/><rect class="wvoiseaxv"/><rect class="n55irwb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:decision-tree" /></template>
<style>
.eg2jk9bwe {
  d: path("m12.71 3.46l2.08 2.08q.71.71 0 1.42l-2.08 2.08q-.71.71-1.42 0L9.21 6.96q-.71-.71 0-1.42l2.08-2.08q.71-.71 1.42 0M8.5 6.25h-1A1.5 1.5 0 0 0 6 7.75v6.5m9.5-8h1a1.5 1.5 0 0 1 1.5 1.5v6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n55irwb-s {
  width: 6.5px;
  height: 6.5px;
  x: 14.75px;
  y: 14.25px;
  rx: 1.5px;
}

.wvoiseaxv {
  width: 6.5px;
  height: 6.5px;
  x: 2.75px;
  y: 14.25px;
  rx: 1.5px;
}

</style>
