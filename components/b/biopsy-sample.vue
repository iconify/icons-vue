<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g9v_k2gpi"/><path class="l5957pehz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biopsy-sample" /></template>
<style>
.g9v_k2gpi {
  d: path("M6.75 3h10.5A1.75 1.75 0 0 1 19 4.75a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 4.75A1.75 1.75 0 0 1 6.75 3M6 6.5v13c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-13m-12 4h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5957pehz {
  fill: currentColor;
  d: path("M9.5 16c0-1.5 1.25-2.5 2.75-2.25s2.5 1.5 2 3s-2.25 2-3.5 1.5C10 17.75 9.5 17 9.5 16");
}

</style>
