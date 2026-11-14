<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odhqo9h5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dose-decrease" /></template>
<style>
.odhqo9h5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 5zA1.75 1.75 0 0 1 7 6.75v12.5A1.75 1.75 0 0 1 5.25 21a1.75 1.75 0 0 1-1.75-1.75V6.75A1.75 1.75 0 0 1 5.25 5m6.5 5za1.75 1.75 0 0 1 1.75 1.75v7.5A1.75 1.75 0 0 1 11.75 21A1.75 1.75 0 0 1 10 19.25v-7.5A1.75 1.75 0 0 1 11.75 10m6.5 6zA1.75 1.75 0 0 1 20 17.75v1.5A1.75 1.75 0 0 1 18.25 21a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 18.25 16m0-12v8.5m-2-2l2 2l2-2");
}

</style>
