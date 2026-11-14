<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u1jv2k3qy"/><path class="pdn6982md"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:junction-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pdn6982md {
  d: path("M10.75 9.5h2.5A1.75 1.75 0 0 1 15 11.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 12.75v-1.5a1.75 1.75 0 0 1 1.75-1.75");
}

.u1jv2k3qy {
  d: path("M9.5 4h5A3.5 3.5 0 0 1 18 7.5v9a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 16.5v-9A3.5 3.5 0 0 1 9.5 4M2 12h4m12 0h4");
}

</style>
