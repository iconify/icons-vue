<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="asdq74kyc"/><path class="h_z5eeykk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basketball-alt" /></template>
<style>
.asdq74kyc {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m16.218-6.718L5.282 18.718m0-13.436l13.436 13.436");
}

.h_z5eeykk {
  d: path("M12 2.5c-.25 5-4.5 9.25-9.5 9.5m9.5 9.5c.25-5 4.5-9.25 9.5-9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
