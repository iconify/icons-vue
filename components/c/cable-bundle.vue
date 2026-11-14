<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnp8x_nbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-bundle" /></template>
<style>
.bnp8x_nbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5za2 2 0 0 1 2 2v10a2 2 0 0 1-2 2a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2M2.5 6C5.5 6 7 8 10 8m-7.5 2c3 0 4.5 2 7.5 2m-7.5 2c3 0 4.5 2 7.5 2m4-8c3 0 4.5 2 7.5 2M14 12c3 0 4.5 2 7.5 2M14 16c3 0 4.5 2 7.5 2");
}

</style>
