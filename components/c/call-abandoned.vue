<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftji7bapd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-abandoned" /></template>
<style>
.ftji7bapd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 5v3.5L16 10l-1.5-2C12 9 9 12 8 14.5l2 1.5l-1.5 4.5H5a2 2 0 0 1-2-2c.5-8 7.5-15 15.5-15.5a2 2 0 0 1 2 2Zm-5 10.5l5 5m0-5l-5 5");
}

</style>
