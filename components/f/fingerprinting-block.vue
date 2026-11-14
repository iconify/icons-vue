<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfu2swmuk"/><path class="m_n8sdb5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fingerprinting-block" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_n8sdb5z {
  d: path("M7.75 17.5v-7a2.75 2.75 0 0 1 5.5 0V14m-2.5 4.5v-8M15 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0m1 2l4-4");
}

.rfu2swmuk {
  d: path("M4.5 14v-3.5a6 6 0 0 1 12 0V12");
}

</style>
