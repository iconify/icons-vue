<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="alp1ribyu"/><path class="r4xl3mbcl"/><path class="wuib9ebtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-balance" /></template>
<style>
.alp1ribyu {
  d: path("M4.5 5.5a7.5 2.5 0 1 0 15 0a7.5 2.5 0 1 0-15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r4xl3mbcl {
  d: path("M4.5 5.5v13a7.5 2.5 0 0 0 15 0v-13");
}

.wuib9ebtp {
  fill: currentColor;
  d: path("M4.5 15a7.5 2.5 0 0 0 15 0v3.5a7.5 2.5 0 0 1-15 0Z");
}

</style>
