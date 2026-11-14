<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5jjyzt5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loading" /></template>
<style>
.c5jjyzt5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V6m0 12v3.5M2.5 12H6m12 0h3.5M5.25 5.25l2.5 2.5m8.5 8.5l2.5 2.5m0-13.5l-2.5 2.5m-11 11l2.5-2.5");
}

</style>
