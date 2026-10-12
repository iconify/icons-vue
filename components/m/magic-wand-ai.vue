<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ssjrmxbxg"/><path class="jvo89s1jl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magic-wand-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvo89s1jl {
  d: path("m5.75 11.25l2.5-2.75l2 2l1.25-1.25l.75.9m5.5 7.6l3.5 3.5m-5-8.25q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25");
}

.ssjrmxbxg {
  width: 11.5px;
  height: 11.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
