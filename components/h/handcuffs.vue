<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqn8rbcfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:handcuffs" /></template>
<style>
.iqn8rbcfr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.48v-1.23a1 1 0 0 1 1-1h.5a1 1 0 0 1 1 1v1.23a3.5 3.5 0 1 1-2.5 0m11.5 0v-1.23a1 1 0 0 1 1-1h.5a1 1 0 0 1 1 1v1.23a3.5 3.5 0 1 1-2.5 0M6.25 11.25V9.5m11.5 1.75V9.5M9.81 5.71h4.38m-4.38 0A2.6 1.5-46.74 1 1 6.25 9.5a2.6 1.5-46.74 1 1 3.56-3.79m7.94 3.79a2.6 1.5 46.74 1 1-3.56-3.79a2.6 1.5 46.74 1 1 3.56 3.79");
}

</style>
