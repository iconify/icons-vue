<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqu3-ji4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:faucet" /></template>
<style>
.tqu3-ji4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5.5h11a5 5 0 0 1 5 5v2h-4v-2a1 1 0 0 0-1-1H4Zm6 0v-3m-2.5 0h5m5.5 13l1.75 3a2 2 0 1 1-3.5 0Z");
}

</style>
