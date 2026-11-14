<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kos_75b8g"/><path class="nxiyobbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:department" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kos_75b8g {
  d: path("M6.5 21.5v-15h3V3h5v3.5h3v15m-14 0h17M9.25 9.25h.01m2.74 0h.01m2.74 0h.01");
}

.nxiyobbaf {
  d: path("M10 12h4a.75.75 0 0 1 .75.75a.75.75 0 0 1-.75.75h-4a.75.75 0 0 1-.75-.75A.75.75 0 0 1 10 12m-.75 4.25h.01m5.49 0h.01m-4.01 5.25V19h2.5v2.5");
}

</style>
