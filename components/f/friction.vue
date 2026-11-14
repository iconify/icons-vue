<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwj_9hb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:friction" /></template>
<style>
.cwj_9hb3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.125 9h5.75a2.625 2.625 0 0 1 2.625 2.625v1.75A2.625 2.625 0 0 1 14.875 16h-5.75A2.625 2.625 0 0 1 6.5 13.375v-1.75A2.625 2.625 0 0 1 9.125 9M3 20.5L5 19l2 1.5L9 19l2 1.5l2-1.5l2 1.5l2-1.5l2 1.5l2-1.5M18 4.25H6m2-2l-2 2l2 2");
}

</style>
