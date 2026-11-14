<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjpedtb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dolphin-mooring" /></template>
<style>
.hjpedtb7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4v11.5M12 3v12.5M17 4v11.5m-12.5-8q7.5 4 15 0m-17 12q2.25-1.5 4.75 0t4.75 0t4.75 0t4.75 0");
}

</style>
