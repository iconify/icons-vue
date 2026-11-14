<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7u7krbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barbell-loaded" /></template>
<style>
.i7u7krbny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 6zA1.75 1.75 0 0 1 6.5 7.75v8.5A1.75 1.75 0 0 1 4.75 18A1.75 1.75 0 0 1 3 16.25v-8.5A1.75 1.75 0 0 1 4.75 6M8 8za1.5 1.5 0 0 1 1.5 1.5v5A1.5 1.5 0 0 1 8 16a1.5 1.5 0 0 1-1.5-1.5v-5A1.5 1.5 0 0 1 8 8m11.25-2zA1.75 1.75 0 0 1 21 7.75v8.5A1.75 1.75 0 0 1 19.25 18a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 19.25 6M16 8za1.5 1.5 0 0 1 1.5 1.5v5A1.5 1.5 0 0 1 16 16a1.5 1.5 0 0 1-1.5-1.5v-5A1.5 1.5 0 0 1 16 8m-6.5 4h5");
}

</style>
