<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mtb0j6n0q"/><path class="tzroa_b7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deploy-approve" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mtb0j6n0q {
  d: path("M19.5 3.5c-5 0-10 3-12 7l5 5c4-2 7-7 7-12");
}

.tzroa_b7a {
  d: path("M8.25 9.25H5l-2.5 2.5l5-1.25m6.25 4.25v.6m-1.45 4.1l-1.05 1.05l1.25-5m.5-7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m1.75 9.5l2 2L21 15.75");
}

</style>
