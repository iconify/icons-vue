<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgbr8o9iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blackhead-extractor" /></template>
<style>
.lgbr8o9iq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m1 2.5L12 12m-.038.038za1.5 1.5 0 0 1 0 2.121l-5.303 5.303a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l5.303-5.303a1.5 1.5 0 0 1 2.121 0");
}

</style>
