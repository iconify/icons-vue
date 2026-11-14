<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k2umkbc4r"/><path class="rwk-g2w0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:internet-radio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2umkbc4r {
  d: path("M6.875 10h10.25a4.375 4.375 0 0 1 4.375 4.375v2.25A4.375 4.375 0 0 1 17.125 21H6.875A4.375 4.375 0 0 1 2.5 16.625v-2.25A4.375 4.375 0 0 1 6.875 10");
}

.rwk-g2w0b {
  d: path("M5.5 15.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m8-2h4m-4 4h4M9.845 7.242a3.5 3.5 0 0 1 4.31 0M7.05 5.05a7 7 0 0 1 9.9 0");
}

</style>
