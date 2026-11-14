<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0u3f_02g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biology" /></template>
<style>
.z0u3f_02g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3h.5a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 9.75 11h-.5A1.75 1.75 0 0 1 7.5 9.25v-4.5A1.75 1.75 0 0 1 9.25 3m2.25 2.5c5.5 0 8 5.5 4.5 11V21M5.5 16.5H16M5 21h14M8.25 15.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
