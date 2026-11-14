<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pngs_5bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:access-granted" /></template>
<style>
.pngs_5bxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21V4.5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v7.75M2.5 21h9.75M15 11.5h.01m-.26 6.5l2 2L21 15.75");
}

</style>
