<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy2wgik4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-number" /></template>
<style>
.hy2wgik4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 5L4 19M9 5L7.5 19m-5-9.5H10m-7.75 5H9.5m2.75 4.5h1.5m2.5 0h1.5m2.5 0h1.5");
}

</style>
