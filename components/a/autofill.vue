<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n1fmn2cbg"/><path class="fdakutbkv"/><path class="k49j5ob_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:autofill" /></template>
<style>
.fdakutbkv {
  fill: currentColor;
  d: path("M13 17.25za1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 13 19.75a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 13 17.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k49j5ob_j {
  d: path("M18.5 4v16.5M16 18l2.5 2.5L21 18");
}

.n1fmn2cbg {
  d: path("M5.625 2.5h4.75A2.625 2.625 0 0 1 13 5.125v10.75a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 3 15.875V5.125A2.625 2.625 0 0 1 5.625 2.5M3 7.75h10m-10 5.5h10");
}

</style>
