<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sz_sb5ble"/><path class="d4xxnibex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:churros" /></template>
<style>
.d4xxnibex {
  d: path("M6.085 16.147L3.368 6.005l.819-1.773l1.595 1.126l.82-1.773l1.595 1.126l2.718 10.142M5.782 5.358L8.5 15.5m4.585-.647l2.718-10.142l1.595-1.126l.82 1.773l1.595-1.126l.819 1.773l-2.717 10.142m.303-10.789L15.5 15.5");
}

.sz_sb5ble {
  d: path("M5 15.5h14l-1.5 4.75A1.5 1.5 0 0 1 16 21.5H8a1.5 1.5 0 0 1-1.5-1.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
