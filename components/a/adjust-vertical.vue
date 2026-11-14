<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yylu98g9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adjust-vertical" /></template>
<style>
.yylu98g9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 3.5V11m0 8v1.5m3-5.5za2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2M8 3.5V5m0 8v7.5M11 9za2 2 0 0 1-2 2H7a2 2 0 0 1-2-2a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2");
}

</style>
