<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uhe7p2n2c"/><path class="rmdq3e2nz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donation-jar-full" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rmdq3e2nz {
  d: path("M9.25 16a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.uhe7p2n2c {
  d: path("M7.75 2.5h8.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 16.25 5h-8.5A1.25 1.25 0 0 1 6.5 3.75A1.25 1.25 0 0 1 7.75 2.5M8 5v2q-3.5 1-3.5 4v8A2.5 2.5 0 0 0 7 21.5h10a2.5 2.5 0 0 0 2.5-2.5v-8q0-3-3.5-4V5m-8.5 5.5h9");
}

</style>
