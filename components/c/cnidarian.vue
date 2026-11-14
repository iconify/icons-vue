<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvhjedc8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cnidarian" /></template>
<style>
.tvhjedc8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12a8 8 0 0 1 16 0Zm3.5 0q-1.5 2.25 0 4.5t0 4.5m4.5-9q-1.5 2.25 0 4.5t0 4.5m4.5-9q-1.5 2.25 0 4.5t0 4.5");
}

</style>
