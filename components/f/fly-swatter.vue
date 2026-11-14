<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzhqhkyjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fly-swatter" /></template>
<style>
.kzhqhkyjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.856 4.356l2.788 2.788a2.625 2.625 0 0 1 0 3.712l-2.788 2.788a2.625 2.625 0 0 1-3.712 0l-2.788-2.788a2.625 2.625 0 0 1 0-3.712l2.788-2.788a2.625 2.625 0 0 1 3.712 0M11.75 12.25L3.5 20.5m8.25-14.75l6.5 6.5m0-6.5l-6.5 6.5");
}

</style>
