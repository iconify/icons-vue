<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffcs2qbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adult-person" /></template>
<style>
.ffcs2qbau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M9 21.5v-6H6.5v-3a2.75 2.75 0 0 1 2.75-2.75h5.5a2.75 2.75 0 0 1 2.75 2.75v3H15v6m-3-4.75v4.75");
}

</style>
