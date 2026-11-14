<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrmjxqbnv"/><path class="cj3xrvjwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genome-sequence" /></template>
<style>
.cj3xrvjwb {
  d: path("M3 9c4.5 0 4.5-6 9-6s4.5 6 9 6M3 13h6m3 0h9M3 17h3m3 0h8M3 21h10m3 0h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrmjxqbnv {
  d: path("M3 3c4.5 0 4.5 6 9 6s4.5-6 9-6");
}

</style>
