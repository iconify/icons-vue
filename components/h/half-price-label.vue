<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r5ows415v"/><path class="tgokhjbxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:half-price-label" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5ows415v {
  d: path("M9.905 4.5h6.97A2.625 2.625 0 0 1 19.5 7.125v9.75a2.625 2.625 0 0 1-2.625 2.625h-6.97a2.63 2.63 0 0 1-2.184-1.169l-3.25-4.875a2.625 2.625 0 0 1 0-2.912l3.25-4.875A2.63 2.63 0 0 1 9.905 4.5M8.25 12h.01");
}

.tgokhjbxc {
  d: path("M10 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4-4v8m2-6.75v5.5");
}

</style>
