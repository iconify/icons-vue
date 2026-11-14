<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb5-nr3pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:full-text-search" /></template>
<style>
.pb5-nr3pd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.25H17m-14.5 5h5.3m-5.3 5h4.9m-4.9 5H9m1-7a5 5 0 1 0 10 0a5 5 0 1 0-10 0m8.5 3.5l3 3");
}

</style>
