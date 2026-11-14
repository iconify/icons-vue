<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxtou8b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:earthquake-magnitude" /></template>
<style>
.kxtou8b8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h3l2-4L10 17.5L12.5 3l2.25 11l1.75-5.5L18 11h3.5m-6 10v-2m2.75 2v-4M21 21v-6");
}

</style>
