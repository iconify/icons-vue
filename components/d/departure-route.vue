<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h9top6bko"/><path class="xw5o89bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:departure-route" /></template>
<style>
.h9top6bko {
  d: path("M4.25 18h7A1.75 1.75 0 0 1 13 19.75a1.75 1.75 0 0 1-1.75 1.75h-7a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 4.25 18M13 19.75c4 0 5-4.75 5-11.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xw5o89bmn {
  d: path("m19.275 4.81l.558.9A1.5 1.5 0 0 1 18.557 8h-1.114a1.5 1.5 0 0 1-1.276-2.29l.558-.9a1.5 1.5 0 0 1 2.55 0");
}

</style>
