<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dax9_vb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-aid-travel" /></template>
<style>
.dax9_vb2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.375 6.5h7.25A4.375 4.375 0 0 1 20 10.875v4.25a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 15.125v-4.25A4.375 4.375 0 0 1 8.375 6.5M9 6.5v-2h6v2M12 10v6m-3-3h6");
}

</style>
