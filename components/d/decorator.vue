<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z2_8lybtw"/><path class="lyqa_3bpe"/><path class="vm1z6pbjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:decorator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyqa_3bpe {
  d: path("m12.699 6.868l3.25 1.71a1.5 1.5 0 0 1 .801 1.328v4.188a1.5 1.5 0 0 1-.801 1.328l-3.25 1.71a1.5 1.5 0 0 1-1.398 0l-3.25-1.71a1.5 1.5 0 0 1-.801-1.328V9.906a1.5 1.5 0 0 1 .801-1.328l3.25-1.71a1.5 1.5 0 0 1 1.398 0");
}

.vm1z6pbjb {
  d: path("M7.25 9L12 11.5L16.75 9M12 11.5v6");
}

.z2_8lybtw {
  d: path("M9.125 3h5.75A6.125 6.125 0 0 1 21 9.125v5.75A6.125 6.125 0 0 1 14.875 21h-5.75A6.125 6.125 0 0 1 3 14.875v-5.75A6.125 6.125 0 0 1 9.125 3");
}

</style>
