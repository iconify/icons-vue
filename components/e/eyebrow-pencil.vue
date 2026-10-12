<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ancp-y3na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eyebrow-pencil" /></template>
<style>
.ancp-y3na {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5c2.5-3 6-4 9.5-3.25m-8.53 12.3l7.02-7.02q.71-.71 1.42 0l1.06 1.06q.71.71 0 1.42l-7.02 7.02q-.71.71-1.42 0l-1.06-1.06q-.71-.71 0-1.42m10.38-9.32l1.42 1.42q.53.53.89-.13l2.23-4.11q.36-.66-.15-.16q-.5.51-1.19.81L14.51 7.4q-.69.3-.16.83");
}

</style>
