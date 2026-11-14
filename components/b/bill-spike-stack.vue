<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cj2y9ibhd"/><path class="pa-le48ty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bill-spike-stack" /></template>
<style>
.cj2y9ibhd {
  d: path("M10.834 19.944L9.25 21L7 19.5L4.75 21L2.5 19.5V7h11v6.4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pa-le48ty {
  d: path("M6 7V3h12v6.5M5.5 11h5m8.106 3.862l2.129 4.496A1.5 1.5 0 0 1 19.38 21.5h-4.26a1.5 1.5 0 0 1-1.355-2.142l2.129-4.496a1.5 1.5 0 0 1 2.712 0M17.25 16.25v1.25m0 2h.01");
}

</style>
