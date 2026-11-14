<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8uomebtn"/><path class="n9nks58ts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coin-dispenser" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n9nks58ts {
  d: path("M9.5 18.75a2.5 1 0 1 0 5 0a2.5 1 0 1 0-5 0");
}

.p8uomebtn {
  d: path("M4.75 2.5h.5A1.75 1.75 0 0 1 7 4.25v7.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 3 11.75v-7.5A1.75 1.75 0 0 1 4.75 2.5m7 0h.5A1.75 1.75 0 0 1 14 4.25v7.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 10 11.75v-7.5a1.75 1.75 0 0 1 1.75-1.75m7 0h.5A1.75 1.75 0 0 1 21 4.25v7.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 17 11.75v-7.5a1.75 1.75 0 0 1 1.75-1.75M4.5 16.5h15l-1.25 5H5.75ZM3 8h4m-4 2.5h4M10 8h4m-4 2.5h4M17 8h4m-4 2.5h4");
}

</style>
