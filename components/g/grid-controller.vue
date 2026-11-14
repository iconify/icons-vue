<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we--33aqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grid-controller" /></template>
<style>
.we--33aqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 5h8.5a5.25 5.25 0 0 1 5.25 5.25v3.5A5.25 5.25 0 0 1 16.25 19h-8.5a5.25 5.25 0 0 1-5.25-5.25v-3.5A5.25 5.25 0 0 1 7.75 5M7 8.5h.01m4.99 0h.01m4.99 0h.01M7 12h.01M12 12h.01M17 12h.01M7 15.5h.01m4.99 0h.01m4.99 0h.01");
}

</style>
