<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fitepdb9p"/><path class="wneuagzbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-operator" /></template>
<style>
.fitepdb9p {
  d: path("M6.625 5.5h5.75A2.625 2.625 0 0 1 15 8.125v1.75a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 4 9.875v-1.75A2.625 2.625 0 0 1 6.625 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wneuagzbm {
  d: path("m15.943 7.123l2-.8A1.5 1.5 0 0 1 20 7.716v2.568a1.5 1.5 0 0 1-2.057 1.393l-2-.8A1.5 1.5 0 0 1 15 9.484v-.968a1.5 1.5 0 0 1 .943-1.393M7 5.5V3h5v2.5m-2.5 7L5 21m4.5-8.5L14 21");
}

</style>
