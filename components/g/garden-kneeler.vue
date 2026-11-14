<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a4fo3-b5d"/><path class="nhai-s2wt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-kneeler" /></template>
<style>
.a4fo3-b5d {
  d: path("M5 6h16.5L19 14H2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhai-s2wt {
  d: path("M2.5 14v3H19v-3m0 3l2.5-8V6m-8.75 2.75h2A1.25 1.25 0 0 1 16 10a1.25 1.25 0 0 1-1.25 1.25h-2A1.25 1.25 0 0 1 11.5 10a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
