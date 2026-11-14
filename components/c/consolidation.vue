<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-l0osbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consolidation" /></template>
<style>
.i-l0osbzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H7V7H2.5Zm7.25 0h4.5V7h-4.5Zm7.25 0h4.5V7H17Zm-10 12h10v7H7ZM4.75 9.75l7.25 2l7.25-2");
}

</style>
