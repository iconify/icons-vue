<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xr3plub-k"/><path class="misn_qbud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alien" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.misn_qbud {
  d: path("M10.7 12.13a2.25 1.25 30 1 0-3.9-2.25a2.25 1.25 30 1 0 3.9 2.25m6.5-2.25a2.25 1.25-30 1 0-3.9 2.25a2.25 1.25-30 1 0 3.9-2.25");
}

.xr3plub-k {
  d: path("M12 2.75c4.6 0 8 3.1 8 7.25c0 5-4.6 11.25-8 11.25S4 15 4 10c0-4.15 3.4-7.25 8-7.25");
}

</style>
