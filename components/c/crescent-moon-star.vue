<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x_nal4bsc"/><path class="q95r-5a2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crescent-moon-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q95r-5a2o {
  d: path("m15.64 6.07l.48 1.07q.14.32.49.35l1.16.12q.35.04.09.27l-.87.78q-.26.24-.19.58l.24 1.14q.08.34-.23.17l-1.01-.58q-.3-.18-.6 0l-1.01.58q-.31.17-.23-.17l.24-1.14q.07-.34-.19-.58l-.87-.78q-.26-.23.09-.27l1.16-.12q.35-.03.49-.35l.48-1.07q.14-.32.28 0");
}

.x_nal4bsc {
  d: path("M10.23 4.54a8.25 8.25 0 1 0 8.98 8.98a6 6 0 1 1-8.98-8.98");
}

</style>
