<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0h1-0b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frost-leaf" /></template>
<style>
.e0h1-0b9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.072 18.146C10.462 19.678 7.234 20.5 3.5 20.5c0-10.5 6.5-17 17-17c0 3.366-.668 6.321-1.922 8.783M3.5 20.5L13 11m5 4v6m-2.5-4.5l5 3m-5 0l5-3");
}

</style>
