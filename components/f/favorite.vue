<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pglgxabbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:favorite" /></template>
<style>
.pglgxabbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3.75l-2 5.5l-6 .25l4.5 3.75L7 19l5-3.25m0-12l2 5.5l6 .25l-4.5 3.75L17 19l-5-3.25");
}

</style>
