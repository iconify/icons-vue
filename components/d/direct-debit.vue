<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ks_5v4bed"/><path class="lmbmm56nt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:direct-debit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ks_5v4bed {
  d: path("m7.25 4.875l4.079-2.04a1.5 1.5 0 0 1 1.342 0l4.079 2.04a1.254 1.254 0 0 1-.561 2.375H7.811a1.254 1.254 0 0 1-.561-2.375M3.5 10h17m-18 10.25H13m-8-7.5v4.75m3.5-4.75v4.75m3.5-4.75v4.75m9.098-.5a3 3 0 1 1-2.598-1.5");
}

.lmbmm56nt {
  d: path("m17.25 14.25l1.25 1.25l-1.25 1.25");
}

</style>
