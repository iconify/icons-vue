<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc1g9qbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-box" /></template>
<style>
.fc1g9qbpo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6C7 2.5 12.5 2.5 15 6l4-3v6l-4-3C12.5 9.5 7 9.5 4.5 6m3.25 0h.01M3.5 11.5v9h17v-9M3.5 16h17");
}

</style>
