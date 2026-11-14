<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfpfuibwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:input-autocomplete" /></template>
<style>
.sfpfuibwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v1a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 7V6A3.5 3.5 0 0 1 6 2.5m0 10.75h12a3.5 3.5 0 0 1 3.5 3.5v1.75A3.5 3.5 0 0 1 18 22H6a3.5 3.5 0 0 1-3.5-3.5v-1.75a3.5 3.5 0 0 1 3.5-3.5m.5-8v2.5m-.5 8.5h10m-10 3h6.5");
}

</style>
