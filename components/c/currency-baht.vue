<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amjyl6r6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:currency-baht" /></template>
<style>
.amjyl6r6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 11.75h5c1.8 0 3-1.25 3-3.25c0-1.75-1.2-3-3-3H8v13h5.5c2 0 3.25-1.4 3.25-3.5c0-1.9-1.25-3.25-3.25-3.25M11.5 3v2.5m0 13V21");
}

</style>
