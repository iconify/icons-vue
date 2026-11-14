<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7iriybos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-combo" /></template>
<style>
.p7iriybos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10H11l-1 11H3.5Zm0 0c0-3 2.5-4 4.25-2.75C8.5 6 11 7 11 10m3-1h7l-1 12h-5Zm3.5 0L19 3.5");
}

</style>
