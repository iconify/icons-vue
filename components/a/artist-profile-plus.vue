<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk6b_8bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:artist-profile-plus" /></template>
<style>
.vk6b_8bka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M3 21.5c0-4.5 3-7.25 7-7.25q2.25 0 3.75.75M18 15v6m-3-3h6");
}

</style>
