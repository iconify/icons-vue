<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m5pv0bp1k"/><path class="awthynk6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ice" /></template>
<style>
.awthynk6v {
  d: path("M3 7.5h13.5L21 3m-4.5 4.5V21M6.25 15v-2.25a2 2 0 0 1 2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m5pv0bp1k {
  d: path("m3.769 6.731l2.962-2.962A2.63 2.63 0 0 1 8.587 3h9.788A2.625 2.625 0 0 1 21 5.625v9.788a2.63 2.63 0 0 1-.769 1.856l-2.962 2.962a2.63 2.63 0 0 1-1.856.769H5.625A2.625 2.625 0 0 1 3 18.375V8.587a2.63 2.63 0 0 1 .769-1.856");
}

</style>
