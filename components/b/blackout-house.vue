<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_ifx8bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blackout-house" /></template>
<style>
.m_ifx8bbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.344 20.5H3.5v-10L12 3.25l8.5 7.25v.856M19 13.75L15.75 18h3.5l-2.75 3.75m-2-7.75l7.25 7.25");
}

</style>
