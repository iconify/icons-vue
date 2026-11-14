<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d313b2bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-words-book" /></template>
<style>
.d313b2bbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14.5c-2-1.25-6-1.5-9-.75v6.75c3-.75 7-.5 9 .75c2-1.25 6-1.5 9-.75v-6.75c-3-.75-7-.5-9 .75m0 0v6.75M8.5 2.5h7a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2l-1.5 2l-1.5-2h-2a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2");
}

</style>
