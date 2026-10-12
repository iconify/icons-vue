<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="w-hf-5brw"/><path class="s1s_17bkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dataset-sharp" /></template>
<style>
.s1s_17bkz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 7.5h.01M6.75 12h.01m-.01 4.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w-hf-5brw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75zM10 7.5h7.5M10 12h7.5M10 16.5h7.5");
}

</style>
