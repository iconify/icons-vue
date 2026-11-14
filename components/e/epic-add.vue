<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcib8fb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:epic-add" /></template>
<style>
.wcib8fb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.578 5.46l-4.574 5.59a1.5 1.5 0 0 0 1.161 2.45h1.528a1.5 1.5 0 0 1 1.474 1.776L8.75 17.5a.993.993 0 0 0 1.758.795l4.595-5.871A1.5 1.5 0 0 0 13.921 10H12.33a1.5 1.5 0 0 1-1.471-1.794l.391-1.956a.953.953 0 0 0-1.672-.79M18 15v6m-3-3h6");
}

</style>
