<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb_n4mphv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kefir" /></template>
<style>
.jb_n4mphv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21.5h10a2 2 0 0 0 2-2v-8c0-2-4-2-4-4V7H9v.5c0 2-4 2-4 4v8a2 2 0 0 0 2 2m3.25-18h3.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 13.75 7h-3.5A1.75 1.75 0 0 1 8.5 5.25a1.75 1.75 0 0 1 1.75-1.75M5 13.5h14");
}

</style>
