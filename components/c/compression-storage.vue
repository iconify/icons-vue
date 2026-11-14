<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_54leblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:compression-storage" /></template>
<style>
.k_54leblf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.875 7.5h2.25a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-2.25a2.625 2.625 0 0 1-2.625-2.625v-3.75A2.625 2.625 0 0 1 10.875 7.5m-2.625 3h7.5M2.5 12h2.75m-2-2.25L5.5 12l-2.25 2.25M21.5 12h-2.75m2-2.25L18.5 12l2.25 2.25");
}

</style>
