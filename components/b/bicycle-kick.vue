<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w250mvb6b"/><path class="nqq05kb5q"/><path class="mf02xib7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bicycle-kick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mf02xib7o {
  d: path("m12 13.25l2 1.25l-.75 2.5h-2.5L10 14.5Zm0 0V10m2 4.5l3-1M13.25 17L15 19.5M10.75 17L9 19.5m1-5l-3-1");
}

.nqq05kb5q {
  d: path("M6.75 15.25a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0");
}

.w250mvb6b {
  d: path("M19.5 11.5a7.5 7.5 0 0 0-15 0m-2-2l2 2l2-2");
}

</style>
