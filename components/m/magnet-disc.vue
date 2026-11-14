<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jr5bizfdj"/><path class="t_twa-a2u"/><path class="q33s4_b-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magnet-disc" /></template>
<style>
.jr5bizfdj {
  d: path("M3 12.75a9 4.5 0 1 0 18 0a9 4.5 0 1 0-18 0Z");
}

.q33s4_b-i {
  d: path("M8.5 12.75a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0ZM6 6.25q6-5.25 12 0");
}

.t_twa-a2u {
  d: path("M3 12.75v3a9 4.5 0 0 0 18 0v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
