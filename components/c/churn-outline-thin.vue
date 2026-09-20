<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q8-0ejn0y"/><path class="igyz-cc5b"/><path class="h7leix15f"/><path class="kx-wgwbez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:churn-outline-thin" /></template>
<style>
.h7leix15f {
  d: path("m15 9 6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.igyz-cc5b {
  d: path("M3 20a5 5 0 0 1 10 0");
}

.kx-wgwbez {
  d: path("m21 9 -6 6");
}

.q8-0ejn0y {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
