<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r9gx__b9j"/><path class="okc431vzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bokeh" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.okc431vzg {
  d: path("M14 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-3 11a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.r9gx__b9j {
  d: path("M3.5 11a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

</style>
