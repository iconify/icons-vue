<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0a2otbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crop-scan" /></template>
<style>
.n0a2otbum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5V3h4.5m9 0H21v4.5m0 9V21h-4.5m-9 0H3v-4.5m9-.25V12m0 1.25C12 11.1 10.5 9.9 8 10c.1 2 1.6 3.2 4 3.25M12 12c0-2.4 1.5-4.2 4-4.25c-.1 2.45-1.6 4.25-4 4.25");
}

</style>
