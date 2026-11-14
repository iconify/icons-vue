<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npcnlcbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fiber-splice-tray" /></template>
<style>
.npcnlcbcd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5V8a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v1.5m-17 6V17a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2v-1.5m-18-3H9m6 0h6.5M9 11h6v3H9Z");
}

</style>
