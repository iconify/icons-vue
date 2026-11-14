<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnm0j3lnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hi-vis-coveralls" /></template>
<style>
.mnm0j3lnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5L12 5l2.5-2.5L17 3l3.5 7.5l-2.25 1l-1.5-3v13H13l-1-8l-1 8H7.25v-13l-1.5 3l-2.25-1L7 3Zm-2.25 7h9.5M7.25 18h9.5");
}

</style>
