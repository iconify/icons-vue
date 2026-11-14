<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j42we8flx"/><path class="rwy8tlbvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:collateral-ratio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j42we8flx {
  d: path("M3.5 6h17M12 3.5v17m-3.5 0h7M5 6v3.5m-3 4h6a3 2.5 0 0 1-6 0M19 6v7.5m-3 0h6a3 2.5 0 0 1-6 0");
}

.rwy8tlbvh {
  d: path("M3 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
