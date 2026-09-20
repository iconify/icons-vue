<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xienbiity"/><path class="ph-bhccoq"/><path class="tobs8svpc"/><path class="oe1ogfbua"/><path class="k4lkwhjuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cost-per-call-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4lkwhjuc {
  d: path("M4 20h9");
}

.oe1ogfbua {
  d: path("m15.5 14 2 2 -2 2");
}

.ph-bhccoq {
  d: path("M10 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.tobs8svpc {
  d: path("M4 16h13");
}

.xienbiity {
  d: path("M7 7a5 5 0 1 0 10 0A5 5 0 1 0 7 7");
}

</style>
