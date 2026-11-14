<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x9wq5-bgu"/><path class="r7rufobdv"/><path class="eahp-xbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hops-vine" /></template>
<style>
.eahp-xbpt {
  d: path("M6.5 3.25Q4.5 7 7 10q2.5-3.5-.5-6.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r7rufobdv {
  d: path("m10.75 12l3.75 2.5l3.75-2.5m-7 3.5L14.5 18l3.25-2.5M5 3q6.5 0 9.5 4.5");
}

.x9wq5-bgu {
  d: path("M14.5 7.5c5 0 5 7.5 0 14c-5-6.5-5-14 0-14");
}

</style>
