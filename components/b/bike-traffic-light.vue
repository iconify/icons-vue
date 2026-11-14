<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6eku7bvs"/><path class="fs700xb7o"/><path class="qe4h11bxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-traffic-light" /></template>
<style>
.e6eku7bvs {
  d: path("M7 2.5h1A3.5 3.5 0 0 1 11.5 6v12A3.5 3.5 0 0 1 8 21.5H7A3.5 3.5 0 0 1 3.5 18V6A3.5 3.5 0 0 1 7 2.5");
}

.fs700xb7o {
  d: path("M6.25 6.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 5.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 5.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m8 2.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4.25 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qe4h11bxa {
  d: path("m16 19.5l1.75-3.5h1.75l.75 3.5");
}

</style>
