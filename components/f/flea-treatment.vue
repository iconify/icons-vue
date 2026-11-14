<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fevtn5uht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flea-treatment" /></template>
<style>
.fevtn5uht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.25v-2a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v2m-8 1.5A1.5 1.5 0 0 1 8 5.25h8a1.5 1.5 0 0 1 1.5 1.5v3.5l-4.5 4h-2l-4.5-4ZM12 16.5l1.5 2a2 2 0 1 1-3 0Z");
}

</style>
