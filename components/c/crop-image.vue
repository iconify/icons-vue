<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eorzvx_sw"/><path class="hic28wblm"/><path class="wvmk1jbtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crop-image" /></template>
<style>
.eorzvx_sw {
  d: path("M6.5 2.5v15h15");
}

.hic28wblm {
  d: path("M2.5 6.5h15v15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wvmk1jbtq {
  d: path("M9.5 14.5L12 12l2.5 2.5m-.5-5h.01");
}

</style>
