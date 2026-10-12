<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pea2gtb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flip-vertical" /></template>
<style>
.pea2gtb0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 12h2.5m2.5 0h2.5m2.5 0h2.5m2.5 0h2.5M8.575 9h6.85q1.2 0 1.2-1.2V4.2q0-1.2-1.01-.55l-7.23 4.7q-1.01.65.19.65m0 6h6.85q1.2 0 1.2 1.2v3.6q0 1.2-1.01.55l-7.23-4.7q-1.01-.65.19-.65");
}

</style>
