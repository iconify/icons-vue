<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bb6qjcxms"/><path class="rziivccrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:building-access" /></template>
<style>
.bb6qjcxms {
  d: path("M11.8 21.5H3V6h3.5V3h5v3H15v6.3m-8-.8h.01m3.99 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rziivccrm {
  d: path("M7.5 21.5V17h3v4.5m5.25-6.5h4.5A1.75 1.75 0 0 1 22 16.75v2.5A1.75 1.75 0 0 1 20.25 21h-4.5A1.75 1.75 0 0 1 14 19.25v-2.5A1.75 1.75 0 0 1 15.75 15M14 17.25h8");
}

</style>
