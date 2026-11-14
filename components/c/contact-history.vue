<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6giiwb8s"/><path class="hcyagl7_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contact-history" /></template>
<style>
.hcyagl7_v {
  d: path("M5.25 2.25v3h3m.875 2.25h5.75a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 6.5 13.875v-3.75A2.625 2.625 0 0 1 9.125 7.5m.375 3h5m-5 3h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t6giiwb8s {
  d: path("M2.5 12a9.5 9.5 0 1 0 2.75-6.75");
}

</style>
