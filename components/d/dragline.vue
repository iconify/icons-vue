<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-aznku7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dragline" /></template>
<style>
.v-aznku7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 17.5h7.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 11.75 21h-7.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75M6.625 11h2.25a2.625 2.625 0 0 1 2.625 2.625v1.25A2.625 2.625 0 0 1 8.875 17.5h-2.25A2.625 2.625 0 0 1 4 14.875v-1.25A2.625 2.625 0 0 1 6.625 11M9.5 11L20 3.5m0 0V13m-2.25 0H22l-.75 4H18.5Z");
}

</style>
