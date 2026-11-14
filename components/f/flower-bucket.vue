<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebtenpb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flower-bucket" /></template>
<style>
.ebtenpb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 11h15L18 21.5H6Zm4 0L6.75 7.5M12 11V5.75M15.5 11l1.75-3.5M4.25 6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6-2a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6 2a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
