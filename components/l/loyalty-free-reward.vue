<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au-7b5yit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loyalty-free-reward" /></template>
<style>
.au-7b5yit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10h10a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 17 21H7a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 7 10M4.25 6.5h15.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 10H4.25A1.75 1.75 0 0 1 2.5 8.25A1.75 1.75 0 0 1 4.25 6.5m7.75 0V21m0-14.5C12 3 8 3 8.5 5C9 6.5 12 6.5 12 6.5m0 0C12 3 16 3 15.5 5C15 6.5 12 6.5 12 6.5");
}

</style>
