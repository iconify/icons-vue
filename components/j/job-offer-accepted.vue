<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i45girxkv"/><path class="heagg9bky"/><path class="mzzxl9bnc"/><path class="oyr5e9bfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:job-offer-accepted" /></template>
<style>
.heagg9bky {
  d: path("m2.5 11l9.5 6l9.5-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i45girxkv {
  d: path("M2.5 11v8.5A1.5 1.5 0 0 0 4 21h16a1.5 1.5 0 0 0 1.5-1.5V11");
}

.mzzxl9bnc {
  d: path("M5.5 13V4.5A1.5 1.5 0 0 1 7 3h10a1.5 1.5 0 0 1 1.5 1.5V13");
}

.oyr5e9bfe {
  d: path("m9 8l2 2l4-4");
}

</style>
