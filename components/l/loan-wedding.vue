<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2vq9dcnb"/><path class="ipg1usant"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-wedding" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipg1usant {
  d: path("M10 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.p2vq9dcnb {
  d: path("M4 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
