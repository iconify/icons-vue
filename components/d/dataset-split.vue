<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lmbo0oiji"/><path class="lc7yc56yf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dataset-split" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lc7yc56yf {
  d: path("M3 9v9q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036t.245.012h5.973M21 10.954V9M3 14.75h9.6M10 9v11.5m4.25-.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-2.25-1.75l4.25-4.5m-1.25 4.5l-4.25-4.5");
}

.lmbo0oiji {
  fill: currentColor;
  d: path("M3 9V6a2.5 2.5 0 0 1 2.5-2.5h13A2.5 2.5 0 0 1 21 6v3Z");
}

</style>
