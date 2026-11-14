<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwbkinbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:airspace-sector" /></template>
<style>
.fwbkinbcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8V6a2 2 0 0 1 2-2h3m8 0h3a2 2 0 0 1 2 2v2m0 8v2a2 2 0 0 1-2 2h-3m-8 0H5a2 2 0 0 1-2-2v-2m7.75-12h2.5m-2.5 16h2.5M3 10.75v2.5m18-2.5v2.5M12 7c.75 0 1 .75 1 1.5v2l4 2V14l-4-1v2.5l1.5 1.25v.75L12 17l-2.5.5v-.75L11 15.5V13l-4 1v-1.5l4-2v-2c0-.75.25-1.5 1-1.5Z");
}

</style>
