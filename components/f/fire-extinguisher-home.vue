<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoeanz4tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-extinguisher-home" /></template>
<style>
.xoeanz4tb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21v-9.5a3.25 3.25 0 0 1 6.5 0V21Zm3.25-12.75V6M7.5 5l7-1M13 6c3.5 0 5 1.5 5 4.5V14");
}

</style>
