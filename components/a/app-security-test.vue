<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwm14acot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:app-security-test" /></template>
<style>
.bwm14acot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h3A3.5 3.5 0 0 1 13 6v12a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 3 18V6a3.5 3.5 0 0 1 3.5-3.5m0 3h3m-3 13h3m7.25-5h4m-3 0v3.25l-2 4.75h6l-2-4.75V13.5");
}

</style>
