<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os74en8da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloud-ceiling" /></template>
<style>
.os74en8da {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11.5a3.25 3.25 0 0 1 .5-6a4.5 4.5 0 0 1 8.5 0a3.25 3.25 0 0 1 1 6Zm-4 10h18m-9-7.25v7.25m-2-5.25l2-2l2 2m-4 3.25l2 2l2-2");
}

</style>
