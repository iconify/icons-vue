<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="fhr6irmkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electricity-meter" /></template>
<style>
.fhr6irmkg {
  d: path("M10 6h4a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 14 9h-4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 10 6m2.003 6.227l-1.544 1.9a.535.535 0 0 0 .416.873a.85.85 0 0 1 .816 1.082l-.191.668a.319.319 0 0 0 .566.275l1.525-2.113a.575.575 0 0 0-.466-.912a.81.81 0 0 1-.769-1.067l.144-.433a.288.288 0 0 0-.497-.273M6.25 12h.01m11.49 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
