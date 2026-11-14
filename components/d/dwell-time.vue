<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwdexbc2b"/><path class="uuf4k9lzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dwell-time" /></template>
<style>
.gwdexbc2b {
  d: path("M3.75 3h9m-9 18h9M5.25 3v3.5l3 5.5l-3 5.5V21m6-18v3.5l-3 5.5l3 5.5V21M19 15.75l3 1.5v3.25L19 22l-3-1.5v-3.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuf4k9lzd {
  d: path("m16 17.25l3 1.5l3-1.5m-3 1.5V22");
}

</style>
