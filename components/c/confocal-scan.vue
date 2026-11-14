<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebwcp565p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:confocal-scan" /></template>
<style>
.ebwcp565p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.328 12.75h9.447a1.75 1.75 0 0 0 1.238-.513L18.5 10.75a1.172 1.172 0 0 0-.828-2H8.225a1.75 1.75 0 0 0-1.238.513L5.5 10.75a1.172 1.172 0 0 0 .828 2m-2.828 4h13l4-4m-17 8h13l4-4M12 3.25v7.5");
}

</style>
