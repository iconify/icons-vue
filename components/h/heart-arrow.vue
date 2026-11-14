<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wczzhtnaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-arrow" /></template>
<style>
.wczzhtnaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 19.5l-6.75-6.75A4.5 4.5 0 0 1 12 7.25a4.5 4.5 0 0 1 6.75 5.5ZM3 3l18 18m0-4.5V21h-4.5");
}

</style>
