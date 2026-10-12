<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdttaxbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coast" /></template>
<style>
.gdttaxbzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.8 2.75h13.65q.8 0 .8.8V17.2q0 .8-.75.53l-1.25-.46q-.75-.27-1.08-1l-.59-1.29q-.33-.73-1.09-.97l-1.73-.52q-.76-.24-.94-1.02l-.39-1.69q-.18-.78-.96-.96l-1.69-.39q-.78-.18-.96-.96l-.39-1.69q-.18-.78-.96-.95l-.69-.16Q7 5.5 6.73 4.75L6.27 3.5q-.27-.75.53-.75m-4.05 8c1.5.25 2.25 1 2.5 2.5s1 2.25 2.5 2.5s2.25 1 2.5 2.5s1 2.25 2.5 2.5");
}

</style>
