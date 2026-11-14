<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abqnffbdc"/><path class="r_u5cjb_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brick" /></template>
<style>
.abqnffbdc {
  d: path("m2.5 11l4-5h15v7l-5 5h-14Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r_u5cjb_d {
  d: path("M2.5 11h14l5-5m-5 5v7");
}

</style>
