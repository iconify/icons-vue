<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axtfm4u2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headline-edit" /></template>
<style>
.axtfm4u2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.1 10.5H2.5v-7h19v7h-2.1M6.5 7h11M3 15.5h8m3.25 6.25l.5-3l4.5-4.5l2.5 2.5l-4.5 4.5Z");
}

</style>
