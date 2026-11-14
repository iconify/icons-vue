<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebkocibxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:led-bulb" /></template>
<style>
.ebkocibxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 18.5V16c-1.75-1-2.5-2.25-2.5-4a5 5 0 0 1 10 0c0 1.75-.75 3-2.5 4v2.5Zm2.5-14.25V2M5 6.5L3.25 4.75M16 6.5l1.75-1.75M15.5 21.5c0-4.5 2-6 6-6q0 6-6 6Zm0 0l3-3");
}

</style>
