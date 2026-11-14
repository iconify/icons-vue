<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biskn-bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carboxyl-group" /></template>
<style>
.biskn-bvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5L9 15h7.5M9 15V7m2.75 5.25v-5M8 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m8.5 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
