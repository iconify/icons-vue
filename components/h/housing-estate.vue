<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myt7txldp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:housing-estate" /></template>
<style>
.myt7txldp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6L5 3.5L7.5 6v4h-5zm7 0L12 3.5L14.5 6v4h-5zm7 0L19 3.5L21.5 6v4h-5zm-14 11L5 14.5L7.5 17v4h-5zm7 0l2.5-2.5l2.5 2.5v4h-5zm7 0l2.5-2.5l2.5 2.5v4h-5z");
}

</style>
