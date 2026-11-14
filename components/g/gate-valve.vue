<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj6_yyb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gate-valve" /></template>
<style>
.oj6_yyb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14h5.5v-2.5h7V14H21M3 19.5h5.5v2h7v-2H21m-18-7V21m18-8.5V21M12 7.5v4M7 5a5 2.5 0 1 0 10 0A5 2.5 0 1 0 7 5");
}

</style>
