<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aqscffw_u"/><path class="mc-7q6bbm"/><path class="feav14cng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:image-multiple" /></template>
<style>
.aqscffw_u {
  d: path("M12 8.5h6a3.5 3.5 0 0 1 3.5 3.5v5.5A3.5 3.5 0 0 1 18 21h-6a3.5 3.5 0 0 1-3.5-3.5V12A3.5 3.5 0 0 1 12 8.5");
}

.feav14cng {
  d: path("M2.5 15V4.5a2 2 0 0 1 2-2h11m-7 16L12 15l3 3m1.25-5.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mc-7q6bbm {
  d: path("M5.5 18V7.5a2 2 0 0 1 2-2h11");
}

</style>
