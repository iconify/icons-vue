<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="udk_j0bbj"/><path class="ef_suabze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-park-store" /></template>
<style>
.ef_suabze {
  d: path("M7.5 19.5v-7h4v7m4.5 2v-7h2.75a2.25 2.25 0 0 1 0 4.5H16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.udk_j0bbj {
  d: path("M4.75 3h12.5A1.75 1.75 0 0 1 19 4.75v.5A1.75 1.75 0 0 1 17.25 7H4.75A1.75 1.75 0 0 1 3 5.25v-.5A1.75 1.75 0 0 1 4.75 3M4 7v12.5h9.2m4.8-7.8V7");
}

</style>
