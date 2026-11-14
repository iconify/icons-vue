<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgtvefb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:base64" /></template>
<style>
.lgtvefb6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 10h2.75a2.625 2.625 0 0 1 2.625 2.625v6.25A2.625 2.625 0 0 1 7.875 21.5h-2.75A2.625 2.625 0 0 1 2.5 18.875v-6.25A2.625 2.625 0 0 1 5.125 10m11 0h2.75a2.625 2.625 0 0 1 2.625 2.625v6.25a2.625 2.625 0 0 1-2.625 2.625h-2.75a2.625 2.625 0 0 1-2.625-2.625v-6.25A2.625 2.625 0 0 1 16.125 10M5 13h3m-3 2.75h3M5 18.5h2m9-2.75h.01m2.99 0h.01M6.5 7.25c1-4.5 10-4.5 11 0m-1.75-1l1.75 1l1-1.75");
}

</style>
