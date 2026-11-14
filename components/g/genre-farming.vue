<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8ihqzvci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genre-farming" /></template>
<style>
.m8ihqzvci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v15m0-9.5c-2.5 0-4.5-2-4.5-4.5C10 4 12 6 12 8.5m0 5.5c-2.5 0-4.5-2-4.5-4.5c2.5 0 4.5 2 4.5 4.5m0-5.5c2.5 0 4.5-2 4.5-4.5C14 4 12 6 12 8.5m0 5.5c2.5 0 4.5-2 4.5-4.5c-2.5 0-4.5 2-4.5 4.5m-8 7h16");
}

</style>
