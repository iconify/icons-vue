<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="un5cyo64d"/><path class="qpo6ebc6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:interoperability" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qpo6ebc6v {
  d: path("M10.5 8.5h8v4a2.25 2.25 0 1 1 0 4v4h-8v-5");
}

.un5cyo64d {
  d: path("M2.5 3.5h8v5a2.25 2.25 0 1 1 0 4v3h-8Z");
}

</style>
