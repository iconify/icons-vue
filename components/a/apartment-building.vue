<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwguczuaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:apartment-building" /></template>
<style>
.mwguczuaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 8h2.75a2.625 2.625 0 0 1 2.625 2.625v7.75A2.625 2.625 0 0 1 8.875 21h-2.75A2.625 2.625 0 0 1 3.5 18.375v-7.75A2.625 2.625 0 0 1 6.125 8m8-5h3.75A2.625 2.625 0 0 1 20.5 5.625v12.75A2.625 2.625 0 0 1 17.875 21h-3.75a2.625 2.625 0 0 1-2.625-2.625V5.625A2.625 2.625 0 0 1 14.125 3M6 12h1m-1 4h1m7-9h1m-1 4h1m2-4h1m-1 4h1");
}

</style>
