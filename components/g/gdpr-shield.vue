<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dvbfptbsw"/><path class="t0xtbabjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gdpr-shield" /></template>
<style>
.dvbfptbsw {
  d: path("m12 2.5l7.5 3V11c0 5-3.25 8.5-7.5 10.5c-4.25-2-7.5-5.5-7.5-10.5V5.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t0xtbabjo {
  d: path("M10.75 11h2.5A1.75 1.75 0 0 1 15 12.75v1.5A1.75 1.75 0 0 1 13.25 16h-2.5A1.75 1.75 0 0 1 9 14.25v-1.5A1.75 1.75 0 0 1 10.75 11m-.5 0V9.5a1.75 1.75 0 0 1 3.5 0V11");
}

</style>
