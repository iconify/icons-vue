<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rjv4fccbb"/><path class="mlhu1qm_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:building-lockdown" /></template>
<style>
.mlhu1qm_b {
  d: path("M8.25 21.5v-5h3v5m3.75-4h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.rjv4fccbb {
  d: path("M12.2 21.5H3v-19h13.5v10M8 6.5h.25m3.25 0h.25M8 10.5h.25m3.25 0h.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
