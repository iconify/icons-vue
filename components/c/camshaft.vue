<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqk1lcbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camshaft" /></template>
<style>
.eqk1lcbrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12H4.5m3 0h3m3 0h3m3 0h1.75M4 9.5a2 2 0 0 1 4 0c0 2-1 4-2 4s-2-2-2-4m6 5a2 2 0 0 0 4 0c0-2-1-4-2-4s-2 2-2 4m6-5a2 2 0 0 1 4 0c0 2-1 4-2 4s-2-2-2-4");
}

</style>
