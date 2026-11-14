<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ie-dbk8ct"/><path class="cjp5t_lsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:debug-print" /></template>
<style>
.cjp5t_lsp {
  d: path("M8.75 14h6.5A1.75 1.75 0 0 1 17 15.75v4a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 19.75v-4A1.75 1.75 0 0 1 8.75 14M7 8V3.5a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1V8M9.5 18h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ie-dbk8ct {
  d: path("M7 17.5H5A2.5 2.5 0 0 1 2.5 15v-4.5A2.5 2.5 0 0 1 5 8h14a2.5 2.5 0 0 1 2.5 2.5V15a2.5 2.5 0 0 1-2.5 2.5h-2");
}

</style>
