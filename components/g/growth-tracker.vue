<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sto2tacti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:growth-tracker" /></template>
<style>
.sto2tacti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 18.75V14m0 1.25c-.1-2.4-1.85-3.8-4.75-3.75c.1 2.4 1.85 3.8 4.75 3.75m0-1.25c-.1-2.9 1.65-5 4.5-5c-.05 2.8-1.8 4.9-4.5 5m11.25 6V5m-3 3l3-3l3 3");
}

</style>
