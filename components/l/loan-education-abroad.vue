<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gsbfybbae"/><path class="yw-bw3fwl"/><path class="cb2ojks1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-education-abroad" /></template>
<style>
.cb2ojks1h {
  d: path("M16.75 18a1.25 3.25 0 1 0 2.5 0a1.25 3.25 0 1 0-2.5 0");
}

.gsbfybbae {
  d: path("m6.183 7.658l5.146-2.573a1.5 1.5 0 0 1 1.342 0l5.146 2.573a1.5 1.5 0 0 1 0 2.684l-5.146 2.573a1.5 1.5 0 0 1-1.342 0l-5.146-2.573a1.5 1.5 0 0 1 0-2.684M6.5 11.25v4.25c0 1.491 2.469 2.981 5.444 3m5.556-6.551v-.699");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yw-bw3fwl {
  d: path("m12 9l-7.5 1.5V15m10.25 3a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m0 0h6.5");
}

</style>
