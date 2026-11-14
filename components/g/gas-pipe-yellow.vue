<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypa9a6b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gas-pipe-yellow" /></template>
<style>
.ypa9a6b_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12zA1.25 1.25 0 0 1 5 13.25v7a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-7A1.25 1.25 0 0 1 3.75 12m16.5 0za1.25 1.25 0 0 1 1.25 1.25v7a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 19 20.25v-7A1.25 1.25 0 0 1 20.25 12M5 13.75h14m-14 6h14M12 2.5c1.5 2 3.25 3.25 3.25 5.25a3.25 3.25 0 0 1-6.5 0c0-1.25.75-2.25 1.5-2.75c.25 1 .75 1.5 1.25 1.75c-.25-1.5 0-3 .5-4.25");
}

</style>
