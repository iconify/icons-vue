<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k4f0--xzx"/><path class="jj2osdcfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beach-camping" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jj2osdcfs {
  d: path("m9.5 19.5l2.5-5l2.5 5M2.5 7Q4.75 5 7 7t4.5 0T16 7t5.5 0");
}

.k4f0--xzx {
  d: path("M4 19.5a8 8 0 0 1 16 0m-17.5 0h19");
}

</style>
