<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs_ap7bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campaign-new" /></template>
<style>
.cs_ap7bdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.868 15.421L6.5 11H3V7h3.5L14 2.5v12.854M5.5 11l1 4M17 6l2.5-1.5m-2 5h3M18 15v6m-3-3h6");
}

</style>
