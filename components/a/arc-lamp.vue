<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zf8finboi"/><path class="d0x70ib1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arc-lamp" /></template>
<style>
.d0x70ib1c {
  d: path("M6.5 17.5V10c0-4 2.5-6.5 6-6.5s6 2 6 4.5m0 0l3 5h-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zf8finboi {
  d: path("M3 21a3.5 3.5 0 0 1 7 0Z");
}

</style>
