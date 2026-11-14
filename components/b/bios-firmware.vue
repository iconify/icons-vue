<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4vc9nbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bios-firmware" /></template>
<style>
.u4vc9nbus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 4.5h5.25A2.625 2.625 0 0 1 15 7.125v5.25A2.625 2.625 0 0 1 12.375 15h-5.25A2.625 2.625 0 0 1 4.5 12.375v-5.25A2.625 2.625 0 0 1 7.125 4.5M8 2.5v2m3.5-2v2M2.5 8h2m-2 3.5h2M8 15v2.5m3.5-2.5v2.5M15 8h2.5M15 11.5h2.5m.5 3v7m-3-3l3 3l3-3");
}

</style>
