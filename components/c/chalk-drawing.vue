<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juv9eckgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chalk-drawing" /></template>
<style>
.juv9eckgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.798 5.141l1.061 1.061a1.75 1.75 0 0 1 0 2.475l-3.182 3.182a1.75 1.75 0 0 1-2.475 0l-1.061-1.061a1.75 1.75 0 0 1 0-2.475l3.182-3.182a1.75 1.75 0 0 1 2.475 0M3 16.5c2-3 3.5 2.5 6-.5c1-1.25 2.5-3.5 3.75-4.5M3 20.5h18");
}

</style>
