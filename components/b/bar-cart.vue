<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q07_t2bxz"/><path class="kl-vf_dyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bar-cart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kl-vf_dyi {
  d: path("M5.75 19.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m9 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M8 11V7.25l1.5-1.5V3M11 3v2.75l1.5 1.5V11m3-7.5h4V5a2 2 0 0 1-4 0Zm2 3.5v4");
}

.q07_t2bxz {
  d: path("M3 4.5h2V18h14v-7H5");
}

</style>
