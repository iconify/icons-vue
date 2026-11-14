<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ptn0dtbna"/><path class="ltzp_hbnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dna-helix" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ltzp_hbnj {
  d: path("M17 2.5C17 7 7 7 7 12s10 5 10 9.5M9.25 12h5.5M9 4h6M9 20h6");
}

.ptn0dtbna {
  d: path("M7 2.5C7 7 17 7 17 12S7 17 7 21.5");
}

</style>
