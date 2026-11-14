<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d7b4u_brx"/><path class="cl5cl4bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breeding" /></template>
<style>
.cl5cl4bfn {
  d: path("M10.5 11a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m7.75-3.25l3-3m-3.25 0h3.25V8");
}

.d7b4u_brx {
  d: path("M3.5 9a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M8 13.5v7m-2.5-3h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
