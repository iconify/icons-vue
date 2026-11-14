<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rxbcllxao"/><path class="g7wfuja_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-sieve" /></template>
<style>
.g7wfuja_n {
  d: path("M2.5 8v3a8 3.5 0 0 0 16 0V8m0 0h3M8 4.75v6.5m5-6.5v6.5M7.5 18h.01m2.99 2.5h.01M13.5 18h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rxbcllxao {
  d: path("M2.5 8a8 3.5 0 1 0 16 0a8 3.5 0 1 0-16 0");
}

</style>
