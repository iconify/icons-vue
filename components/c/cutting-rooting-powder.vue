<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqpuy7baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cutting-rooting-powder" /></template>
<style>
.hqpuy7baa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.375 11.5h3.25A4.375 4.375 0 0 1 18 15.875v1.25a4.375 4.375 0 0 1-4.375 4.375h-3.25A4.375 4.375 0 0 1 6 17.125v-1.25a4.375 4.375 0 0 1 4.375-4.375M7.5 8.75h9M12 5.5v3.25m0-3.25c0-2-2-3-4.5-3c0 2 2 3 4.5 3m0 0c0-2 2-3 4.5-3c0 2-2 3-4.5 3");
}

</style>
