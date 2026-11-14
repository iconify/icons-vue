<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwzooerip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:common-time" /></template>
<style>
.mwzooerip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h7.9m6.1 0h5m-19 4.25h2.9m14.9 0h1.2M2.5 12h1.9m5.4 0h11.7m-19 4.25h2.9m14.9 0h1.2m-19 4.25h7.9m6.1 0h5m-4-13.25a6.25 6.25 0 1 0 0 9.5");
}

</style>
