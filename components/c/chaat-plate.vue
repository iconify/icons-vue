<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p1ekqe7je"/><path class="s50us_dwc"/><path class="c9pk-5baf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chaat-plate" /></template>
<style>
.c9pk-5baf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.5 8.75l3.75-4.5m-17.5 9h18.5c-.5 3.75-4.5 6.5-9.25 6.5S3.25 17 2.75 13.25");
}

.p1ekqe7je {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13C6 9.5 8.75 7.5 12 7.5s6 2 6.5 5.5Z");
}

.s50us_dwc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10.75h.01m3.74-.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
