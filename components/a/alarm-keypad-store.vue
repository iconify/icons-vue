<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc9hswbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alarm-keypad-store" /></template>
<style>
.lc9hswbug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.4 21.5H2.5v-19h14v9.7M6 6.25h7M6 10h.01m3.49 0h.01M13 10h.01M6 13.25h.01m3.49 0h.01m3.49 0h.01M6 16.5h.01m3.49 0h.01m3.49 0h.01m1.74 2.75h6.5l-1-1.25v-1a2.25 2.25 0 0 0-4.5 0v1Zm2.5 2.25h1.5");
}

</style>
