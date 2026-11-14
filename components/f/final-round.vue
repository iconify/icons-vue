<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cugwvcc_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:final-round" /></template>
<style>
.cugwvcc_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3h11.5A1.75 1.75 0 0 1 20 4.75v6.5A1.75 1.75 0 0 1 18.25 13H6.75A1.75 1.75 0 0 1 5 11.25v-6.5A1.75 1.75 0 0 1 6.75 3M5 3v18.5M10 3v10m5-10v10M5 8h15M7.5 5.5h.01m9.99 0h.01m-5.01 5h.01");
}

</style>
