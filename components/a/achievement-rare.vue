<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kerdltm6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:achievement-rare" /></template>
<style>
.kerdltm6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5.5h8l3.5 4.5L10 20.5L2.5 10ZM2.5 10h15m1.75-7.5q0 2.25 2.25 2.25q-2.25 0-2.25 2.25q0-2.25-2.25-2.25q2.25 0 2.25-2.25Z");
}

</style>
