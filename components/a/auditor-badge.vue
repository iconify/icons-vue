<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g7vtybvea"/><path class="iozeegaff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:auditor-badge" /></template>
<style>
.g7vtybvea {
  d: path("m7 2.5l5 3l5-3m-5.5 3h1A1.5 1.5 0 0 1 14 7a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 7a1.5 1.5 0 0 1 1.5-1.5m-2 3h5A3.5 3.5 0 0 1 18 12v6a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 18v-6a3.5 3.5 0 0 1 3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iozeegaff {
  d: path("m9 16l2 2l4-4");
}

</style>
