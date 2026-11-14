<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q__slhuuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:herbal-remedy" /></template>
<style>
.q__slhuuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18c0 5.5-4 8.5-9 8.5s-9-3-9-8.5m11.5 2.5l5-9.5m-13 4.5C6.5 5 9 3 13 3c0 3.5-2.5 5.5-6.5 5.5");
}

</style>
