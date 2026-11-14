<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh9kl_b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:escalate-manager" /></template>
<style>
.qh9kl_b_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.572 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.437 0 2.76.257 3.882.724M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
