<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhb1_demx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kitchen-sink" /></template>
<style>
.dhb1_demx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19m-17 0v5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2v-5m-2.5 0v-6a2.5 2.5 0 0 0-5 0v2");
}

</style>
