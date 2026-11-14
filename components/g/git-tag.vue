<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c7m0z8btx"/><path class="aae9q5xrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:git-tag" /></template>
<style>
.aae9q5xrk {
  d: path("M9.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-7 0h3");
}

.c7m0z8btx {
  d: path("M10.967 5.5h6.908A2.625 2.625 0 0 1 20.5 8.125v7.75a2.625 2.625 0 0 1-2.625 2.625h-6.908a2.63 2.63 0 0 1-2.236-1.249l-2.384-3.875a2.63 2.63 0 0 1 0-2.752l2.384-3.875A2.63 2.63 0 0 1 10.967 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
