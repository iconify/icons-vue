<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7h0yct4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:compound-microscope" /></template>
<style>
.x7h0yct4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 2.5h.5a1.75 1.75 0 0 1 1.75 1.75v5.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 8.5 9.75v-5.5a1.75 1.75 0 0 1 1.75-1.75M12.5 6C19 6 20 14 16 21M5 21h14m-8.5-9.5v1.75M6 16h12");
}

</style>
