<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7_77lgut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deck-chair" /></template>
<style>
.w7_77lgut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.25 3.5l5 10h11.5m-11.5 0L6 19.5m12.75-6l1.75 6m-11.25-6l5.5 6m-12 1.75h18.5");
}

</style>
