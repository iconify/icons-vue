<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sctraq26n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-centre" /></template>
<style>
.sctraq26n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0m-11.17 10h4.34a1.5 1.5 0 0 1 1.471 1.794l-.4 2A1.5 1.5 0 0 1 13.77 21.5h-3.54a1.5 1.5 0 0 1-1.471-1.206l-.4-2A1.5 1.5 0 0 1 9.83 16.5m2.17 0v-4m0 2c-2 0-4-1-4.5-3c2 0 4 1 4.5 3m0-1c2 0 4-1 4.5-2c-2-.25-4 .5-4.5 2");
}

</style>
