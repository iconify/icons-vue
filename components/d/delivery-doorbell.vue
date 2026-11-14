<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ewyga_bja"/><path class="u5xpk8bdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-doorbell" /></template>
<style>
.ewyga_bja {
  d: path("M6.875 2.5h3a4.375 4.375 0 0 1 4.375 4.375v10.25A4.375 4.375 0 0 1 9.875 21.5h-3A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u5xpk8bdr {
  d: path("M5.5 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0m.25 7.5h5.5m5.871-9.621a3 3 0 0 1 0 4.242m2.122-6.364a6 6 0 0 1 0 8.486");
}

</style>
