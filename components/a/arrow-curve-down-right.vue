<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ph8gnzbfo"/><path class="dh9t8vo3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-curve-down-right" /></template>
<style>
.dh9t8vo3f {
  d: path("M11 21h5v-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ph8gnzbfo {
  d: path("M8 3v7c0 2 .75 3.75 2 5l6 6");
}

</style>
