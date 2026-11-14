<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg68y8z2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bleeding" /></template>
<style>
.mg68y8z2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3S4.5 9 4.5 13a5.5 5.5 0 0 0 11 0C15.5 9 10 3 10 3m8 10s-2 2.5-2 4a2 2 0 0 0 4 0c0-1.5-2-4-2-4");
}

</style>
