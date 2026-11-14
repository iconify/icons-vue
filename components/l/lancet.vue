<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gtpnnwb2p"/><path class="v7v875bbc"/><path class="bl3gq9btu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lancet" /></template>
<style>
.bl3gq9btu {
  fill: currentColor;
  d: path("M7 13.75c.75 1 1.25 1.5 1.25 2C8.25 16.5 7.75 17 7 17s-1.25-.5-1.25-1.25c0-.5.5-1 1.25-2");
}

.gtpnnwb2p {
  d: path("M17.889 4.111za2.25 2.25 0 0 1 0 3.182l-4.596 4.596a2.25 2.25 0 0 1-3.182 0a2.25 2.25 0 0 1 0-3.182l4.596-4.596a2.25 2.25 0 0 1 3.182 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7v875bbc {
  d: path("m18.78 3.366l.354.354a1 1 0 0 1 0 1.414a1 1 0 0 1-1.414 0l-.354-.354a1 1 0 0 1 0-1.414a1 1 0 0 1 1.414 0M9.5 11.75L8 13.25M2.5 19.5c2-2 5.5-2 7.5 0");
}

</style>
