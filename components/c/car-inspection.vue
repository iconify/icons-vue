<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mme-5accm"/><path class="p06m2ib_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-inspection" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mme-5accm {
  d: path("M4 13H2.5v-3A1.5 1.5 0 0 1 4 8.5h1.5l2.5-4h6l2.75 4H18a1.5 1.5 0 0 1 1.5 1.5v3H16m-4.5 0h-3");
}

.p06m2ib_n {
  d: path("M4 13a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 4 13m7.5 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m3.25 5l2 2L21 15.75");
}

</style>
