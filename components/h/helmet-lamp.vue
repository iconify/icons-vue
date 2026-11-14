<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="seka_ekbc"/><path class="nq5m5wbor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:helmet-lamp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nq5m5wbor {
  d: path("M13.75 11.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4.25-1L21.5 8M18 12.5l3.5 2.5");
}

.seka_ekbc {
  d: path("M3 17c0-6.5 3.5-11 8-11c2.25 0 4 1.25 4.75 3.25M2.5 17h17M17 17l-.5-3.25");
}

</style>
