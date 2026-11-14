<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnly369vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bill-of-materials" /></template>
<style>
.dnly369vk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 3.75h2.5A1.75 1.75 0 0 1 15 5.5V7a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 7V5.5a1.75 1.75 0 0 1 1.75-1.75m1.25 5v6.5m-7.25 0v-3h14.5v3m-15 0h1A1.75 1.75 0 0 1 7 17v1.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 2.5 18.5V17a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1A1.75 1.75 0 0 1 14.25 17v1.5a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75V17a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1A1.75 1.75 0 0 1 21.5 17v1.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 17 18.5V17a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
