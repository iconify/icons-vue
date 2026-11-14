<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xz9sxsgtq"/><path class="aezb2i3kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:good-bacteria" /></template>
<style>
.aezb2i3kc {
  d: path("M6.5 7.5c1.5-1.25 2 1.25 3.5 0s2 1.25 3.5 0M18 15v6m-3-3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xz9sxsgtq {
  d: path("M6.5 3.5h7a4 4 0 0 1 4 4a4 4 0 0 1-4 4h-7a4 4 0 0 1-4-4a4 4 0 0 1 4-4");
}

</style>
