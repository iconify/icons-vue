<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pfa_6tbda"/><path class="ci322rbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cattail" /></template>
<style>
.ci322rbkv {
  d: path("M2.5 19.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfa_6tbda {
  d: path("M9.75 4.5zA2.25 2.25 0 0 1 12 6.75v4.5a2.25 2.25 0 0 1-2.25 2.25a2.25 2.25 0 0 1-2.25-2.25v-4.5A2.25 2.25 0 0 1 9.75 4.5m0-2v2m0 9v5m0 0C13 15 15.5 10 15.5 5.5");
}

</style>
