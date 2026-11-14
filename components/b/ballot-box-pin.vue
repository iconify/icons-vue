<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt2dpibpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ballot-box-pin" /></template>
<style>
.lt2dpibpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11h10a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18v-3.5A3.5 3.5 0 0 1 7 11m5 0c-2-2-3.75-3-3.75-4.75a3.75 3.75 0 0 1 7.5 0C15.75 8 14 9 12 11m-3.5 3.5h7M12 6.25h.01");
}

</style>
