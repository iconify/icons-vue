<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5iez6_pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contact-lens" /></template>
<style>
.k5iez6_pe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 21.25V17.5a5.25 5.25 0 0 1 10.5 0v3.75ZM5.5 5.66a8 8 0 0 0 13 0a1.5 1.5 0 0 0-2.44-1.75a5 5 0 0 1-8.12 0A1.5 1.5 0 0 0 5.5 5.66");
}

</style>
