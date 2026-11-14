<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oro8bibwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:analytics-funnel" /></template>
<style>
.oro8bibwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.164 17.049L9.75 19v-7.75L3.5 4h15l-5.25 7.25v4.449M16 21.5v-3m2.75 3v-5.75m2.75 5.75v-8");
}

</style>
