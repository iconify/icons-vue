<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-m2vrbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:leaf-alert" /></template>
<style>
.h-m2vrbcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 18.75c-.75-8.5 3.5-14 14-14c0 10.5-5.5 14.75-14 14M3 21l10.5-10.5");
}

</style>
