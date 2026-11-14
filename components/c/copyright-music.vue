<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pakpcbb-c"/><path class="cux-nvb7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:copyright-music" /></template>
<style>
.cux-nvb7p {
  d: path("M18.5 16a1.75 1.75 0 1 0 0 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pakpcbb-c {
  d: path("M3 17.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m6 0v-14m0 0c1.5 2.5 5.5 3 6 6.5m-2.25 7.25a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
