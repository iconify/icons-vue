<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l-tpeebwp"/><path class="cu1j34blf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:all-time-high" /></template>
<style>
.cu1j34blf {
  d: path("M14.5 7.5h5v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l-tpeebwp {
  d: path("M3 4h18M3 20l5.5-6.5l4 3.5l7-9.5");
}

</style>
