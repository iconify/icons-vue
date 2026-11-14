<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uhq2dydyb"/><path class="kax1rnxyb"/><path class="fb8cv3u9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:linen-cart" /></template>
<style>
.fb8cv3u9f {
  d: path("m20 6l1.5-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kax1rnxyb {
  fill: currentColor;
  d: path("M4.25 21.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m14 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

.uhq2dydyb {
  d: path("M4 6v13.5M20 6v13.5m-16-6h16m-16 6h16M7.5 10h9a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 12v-.5A1.5 1.5 0 0 1 7.5 10M9 6.5h6A1.5 1.5 0 0 1 16.5 8v.5A1.5 1.5 0 0 1 15 10H9a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 9 6.5");
}

</style>
