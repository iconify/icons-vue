<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi36qcc3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:area-rectangle" /></template>
<style>
.yi36qcc3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5H16V15H2.5ZM4 17.75l-1.5 1.5l1.5 1.5m-1.5-1.5H16m-1.5-1.5l1.5 1.5l-1.5 1.5M18.75 5l1.5-1.5l1.5 1.5m-1.5-1.5V15m-1.5-1.5l1.5 1.5l1.5-1.5");
}

</style>
