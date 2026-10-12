<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tep_r1b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:binary" /></template>
<style>
.tep_r1b-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 2.75a2.5 2.5 0 0 1 2.5 2.5v2a2.5 2.5 0 0 1-5 0v-2a2.5 2.5 0 0 1 2.5-2.5m-8 11.5a2.5 2.5 0 0 1 2.5 2.5v2a2.5 2.5 0 0 1-5 0v-2a2.5 2.5 0 0 1 2.5-2.5M7.25 4L9 2.75v7m6.25 5.75L17 14.25v7");
}

</style>
