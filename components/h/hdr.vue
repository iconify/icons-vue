<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff7jv6lvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hdr" /></template>
<style>
.ff7jv6lvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5v7m4-7v7m-4-3.5h4M9 8.5h1a3.5 3.5 0 0 1 0 7H9Zm7 7v-7h2.75a2 2 0 0 1 0 4H16m2.75 0l2.25 3");
}

</style>
