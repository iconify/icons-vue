<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dle55mape"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gondola-cabin" /></template>
<style>
.dle55mape {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 5l19-2.5M12 3.75V7m-1.625 0h3.25A4.375 4.375 0 0 1 18 11.375v4.25A4.375 4.375 0 0 1 13.625 20h-3.25A4.375 4.375 0 0 1 6 15.625v-4.25A4.375 4.375 0 0 1 10.375 7M6 13h12");
}

</style>
