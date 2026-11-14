<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sylm3_enk"/><path class="ax0i0xbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:census-form-check" /></template>
<style>
.ax0i0xbrg {
  d: path("M10.75 2.5h2.5A1.75 1.75 0 0 1 15 4.25A1.75 1.75 0 0 1 13.25 6h-2.5A1.75 1.75 0 0 1 9 4.25a1.75 1.75 0 0 1 1.75-1.75M7.5 9.75h3m3-.25L15 11l2.25-2.25m-9.75 5h9m-9 4h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sylm3_enk {
  d: path("M7.5 4h9A3.5 3.5 0 0 1 20 7.5V18a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18V7.5A3.5 3.5 0 0 1 7.5 4");
}

</style>
