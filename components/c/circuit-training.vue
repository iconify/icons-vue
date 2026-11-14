<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r2gwdbbsx"/><path class="lgkezfhfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:circuit-training" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgkezfhfa {
  d: path("M15.25 6H18V3.25m-9.875 6.5zA1.375 1.375 0 0 1 9.5 11.125v1.75a1.375 1.375 0 0 1-1.375 1.375a1.375 1.375 0 0 1-1.375-1.375v-1.75A1.375 1.375 0 0 1 8.125 9.75m7.75 0za1.375 1.375 0 0 1 1.375 1.375v1.75a1.375 1.375 0 0 1-1.375 1.375a1.375 1.375 0 0 1-1.375-1.375v-1.75a1.375 1.375 0 0 1 1.375-1.375M9.5 12h5");
}

.r2gwdbbsx {
  d: path("M20.25 14.25A8.5 8.5 0 1 1 18 6");
}

</style>
