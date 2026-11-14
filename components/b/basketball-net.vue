<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gkgh-8bqy"/><path class="yao28lupv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basketball-net" /></template>
<style>
.gkgh-8bqy {
  d: path("M4 6a8 2.5 0 1 0 16 0A8 2.5 0 1 0 4 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yao28lupv {
  d: path("m4 6l3 13.5h10L20 6M8 8.5l6.5 11m1.5-11l-6.5 11");
}

</style>
