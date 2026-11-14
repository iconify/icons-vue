<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b_l-on5rr"/><path class="ni9e35z8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badge-speed" /></template>
<style>
.b_l-on5rr {
  d: path("M4.5 9.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ni9e35z8v {
  d: path("M8.5 16.25v5.25l3.5-1.75l3.5 1.75v-5.25m-3.593-9.454l-1.726 2.656a.678.678 0 0 0 .569 1.048a.994.994 0 0 1 .969 1.218l-.094.407a.276.276 0 0 0 .503.207l1.714-2.769A.696.696 0 0 0 13.25 8.5a.976.976 0 0 1-.947-1.213L12.375 7a.259.259 0 0 0-.468-.204");
}

</style>
