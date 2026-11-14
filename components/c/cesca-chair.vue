<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q37iwnbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cesca-chair" /></template>
<style>
.q37iwnbtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 21.5H6.5a2 2 0 0 1-2-2V14a2 2 0 0 1 2-2H16m.25-8.5h1.5a1.75 1.75 0 0 1 1.75 1.75v5A1.75 1.75 0 0 1 17.75 12h-1.5a1.75 1.75 0 0 1-1.75-1.75v-5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
