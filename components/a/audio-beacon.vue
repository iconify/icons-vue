<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdx_xobmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:audio-beacon" /></template>
<style>
.qdx_xobmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h3l5-3.5v11L6 12H3Zm2 4v8.5m8.75-12.75a3.5 3.5 0 0 1 0 4.5M16 5.75a6.5 6.5 0 0 1 0 8.5M18.25 4a9.5 9.5 0 0 1 0 12");
}

</style>
