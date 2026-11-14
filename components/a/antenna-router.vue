<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwuonfu1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:antenna-router" /></template>
<style>
.fwuonfu1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11h12a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5v-2A3.5 3.5 0 0 1 6 11m.5 0l-3-8M7 15.5h.01m3.49 0h.01");
}

</style>
