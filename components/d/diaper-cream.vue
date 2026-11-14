<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3y9nn_4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diaper-cream" /></template>
<style>
.n3y9nn_4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.654 17.232q-.09.617-.154 1.268H9c-.5-5-2-8.5-6-9v-5h16.5v5c-2.031.254-3.417 1.281-4.356 2.886M3 7.5h16.5M16 15h5l-1 4.5h-3Zm2 4.5h1a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

</style>
