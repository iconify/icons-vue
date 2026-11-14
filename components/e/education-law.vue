<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrc0gabro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:education-law" /></template>
<style>
.zrc0gabro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5c-3-2-6.5-2.5-9.5-2v-7c3-.5 6.5 0 9.5 2c3-2 6.5-2.5 9.5-2v7c-3-.5-6.5 0-9.5 2m0-7v7m.614-17.77L16 5a1.602 1.602 0 0 1 0 3l-3.386 1.27a1.75 1.75 0 0 1-1.228 0L8 8a1.602 1.602 0 0 1 0-3l3.386-1.27a1.75 1.75 0 0 1 1.228 0M17.5 7.5V10");
}

</style>
