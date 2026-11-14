<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7bq7w9vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bamboo-material" /></template>
<style>
.x7bq7w9vz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3za2 2 0 0 1 2 2v14.5a2 2 0 0 1-2 2a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2M5 7.5h4m-4 4.75h4M5 17h4m0-9.5c2.5-3 6.5-4.5 10.5-4c-2 3.5-6 5-10.5 4m0 4.75c3-.75 7-.25 10.5 2.25c-4 1-7.5 0-10.5-2.25");
}

</style>
