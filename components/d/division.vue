<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds946u5-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:division" /></template>
<style>
.ds946u5-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.5h2.5A1.75 1.75 0 0 1 15 4.25v1A1.75 1.75 0 0 1 13.25 7h-2.5A1.75 1.75 0 0 1 9 5.25v-1a1.75 1.75 0 0 1 1.75-1.75m-6.5 10h3.5a1.75 1.75 0 0 1 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-2.5a1.75 1.75 0 0 1 1.75-1.75M12 7v2.75m-6 0h11.75M6 9.75v2.75m11.75-2.75v2.75M14 15v-1.5a1 1 0 0 1 1-1h1m3.5 0h1a1 1 0 0 1 1 1V15m0 3v1.5a1 1 0 0 1-1 1h-1m-3.5 0h-1a1 1 0 0 1-1-1V18");
}

</style>
