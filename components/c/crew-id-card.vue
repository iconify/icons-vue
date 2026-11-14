<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y8f0is38y"/><path class="wyor1x4ks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crew-id-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wyor1x4ks {
  d: path("M7.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1 7c0-1.5 1.25-2.25 3-2.25s3 .75 3 2.25m3-7H18m-2.5 4H18");
}

.y8f0is38y {
  d: path("M7.375 5.5h9.25A4.375 4.375 0 0 1 21 9.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 16.125v-6.25A4.375 4.375 0 0 1 7.375 5.5M10 5.5v-2a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2");
}

</style>
