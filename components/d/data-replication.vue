<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eyp4w1b5b"/><path class="abf_15vxo"/><path class="e24t4jmdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-replication" /></template>
<style>
.abf_15vxo {
  d: path("M2.5 11.5C2.5 12.9 5.4 14 9 14s6.5-1.1 6.5-2.5");
}

.e24t4jmdl {
  d: path("M8.5 5c0-1.4 2.9-2.5 6.5-2.5s6.5 1.1 6.5 2.5v10.5c0 1.1-1.5 2-3.5 2.5");
}

.eyp4w1b5b {
  d: path("M2.5 11.5C2.5 10.1 5.4 9 9 9s6.5 1.1 6.5 2.5V19c0 1.4-2.9 2.5-6.5 2.5S2.5 20.4 2.5 19Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
