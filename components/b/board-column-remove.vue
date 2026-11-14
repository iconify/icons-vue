<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekdkustfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:board-column-remove" /></template>
<style>
.ekdkustfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5zA2.25 2.25 0 0 1 7 4.75v14.5a2.25 2.25 0 0 1-2.25 2.25a2.25 2.25 0 0 1-2.25-2.25V4.75A2.25 2.25 0 0 1 4.75 2.5m7.25 0za2.25 2.25 0 0 1 2.25 2.25v8.5A2.25 2.25 0 0 1 12 15.5a2.25 2.25 0 0 1-2.25-2.25v-8.5A2.25 2.25 0 0 1 12 2.5m7.25 0za2.25 2.25 0 0 1 2.25 2.25v4.5a2.25 2.25 0 0 1-2.25 2.25A2.25 2.25 0 0 1 17 9.25v-4.5a2.25 2.25 0 0 1 2.25-2.25M15 18h6");
}

</style>
