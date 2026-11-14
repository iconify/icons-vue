<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o2csh_b0k"/><path class="kv5ylacwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-error" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kv5ylacwr {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5M15 15l6 6m0-6l-6 6");
}

.o2csh_b0k {
  d: path("M3.5 3v17.5h8.7");
}

</style>
