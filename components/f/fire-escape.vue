<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eikbuwjbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-escape" /></template>
<style>
.eikbuwjbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 2.5h5a1.75 1.75 0 0 1 1.75 1.75v15.5a1.75 1.75 0 0 1-1.75 1.75h-5A1.75 1.75 0 0 1 13 19.75V4.25a1.75 1.75 0 0 1 1.75-1.75M3.5 7H13m-9.5 7H13m-9.5 7H13M4.5 7l7.5 7m-7.5 0l7.5 7M3.5 4v17M16 6h.01M19 6h.01M16 11h.01M19 11h.01M16 16h.01M19 16h.01");
}

</style>
