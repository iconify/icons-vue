<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jzf-qrdrn"/><path class="kgoc01t9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dsl-port" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzf-qrdrn {
  d: path("M6.875 3h10.25A4.375 4.375 0 0 1 21.5 7.375v2.25A4.375 4.375 0 0 1 17.125 14H6.875A4.375 4.375 0 0 1 2.5 9.625v-2.25A4.375 4.375 0 0 1 6.875 3");
}

.kgoc01t9k {
  d: path("M8.75 6.5h6.5A1.75 1.75 0 0 1 17 8.25v.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 8.75v-.5A1.75 1.75 0 0 1 8.75 6.5M11 14h2a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 9.5 16v-.5A1.5 1.5 0 0 1 11 14m1 3.5V19a2.5 2.5 0 0 0 2.5 2.5H19");
}

</style>
