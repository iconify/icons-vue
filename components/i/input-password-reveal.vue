<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rwuimmbgs"/><path class="sikva5d1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:input-password-reveal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rwuimmbgs {
  d: path("M6.75 3h10.5a4.25 4.25 0 0 1 4.25 4.25a4.25 4.25 0 0 1-4.25 4.25H6.75A4.25 4.25 0 0 1 2.5 7.25A4.25 4.25 0 0 1 6.75 3M5 18c1.6-2.4 4-3.5 7-3.5s5.4 1.1 7 3.5c-1.6 2.4-4 3.5-7 3.5S6.6 20.4 5 18M6.5 7.25h.01m3.49 0h.01m3.49 0h.01m3.49 0h.01");
}

.sikva5d1b {
  d: path("M10.25 18a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
