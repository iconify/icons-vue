<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixf_8y22x"/><path class="mqtixbwqo"/><path class="h1x6gzy2a"/><path class="uogqi4bmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cors-outline-thin" /></template>
<style>
.h1x6gzy2a {
  d: path("M4.5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixf_8y22x {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.uogqi4bmc {
  d: path("m8 13 3 3 5 -5");
}

</style>
