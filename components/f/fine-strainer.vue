<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="togv5ib1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fine-strainer" /></template>
<style>
.togv5ib1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.499 8h7.002a1.75 1.75 0 0 1 1.523 2.611l-3.501 6.194a1.75 1.75 0 0 1-3.046 0l-3.501-6.194A1.75 1.75 0 0 1 6.499 8M16.5 8l4-4m-14 7.5h7M8.25 15h3.5");
}

</style>
