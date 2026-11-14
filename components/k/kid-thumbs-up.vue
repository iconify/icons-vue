<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2235o6nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kid-thumbs-up" /></template>
<style>
.j2235o6nu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 11h2A1.75 1.75 0 0 1 8 12.75v7a1.75 1.75 0 0 1-1.75 1.75h-2a1.75 1.75 0 0 1-1.75-1.75v-7A1.75 1.75 0 0 1 4.25 11M8 11h2.5L12 5c.5-2.25 4-2.25 4 .5v5h3a2.5 2.5 0 0 1 2.5 2.5l-1.25 6.25a2.5 2.5 0 0 1-2.5 2.25H8Zm5 5.5h7.75");
}

</style>
