<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w13f0mbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-aisle" /></template>
<style>
.w13f0mbib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8.5c0-2.25 1.5-3 1.75-4.5a1.25 1.25 0 0 1 2.5 0C13.5 5.5 15 6.25 15 8.5m-7 0h8a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H8A1.5 1.5 0 0 1 6.5 10A1.5 1.5 0 0 1 8 8.5m-.5 3v8a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2v-8");
}

</style>
