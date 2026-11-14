<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_uygfblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bird-scarer" /></template>
<style>
.j_uygfblr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5v-6a3 3 0 0 1 0 6m0 0h6a3 3 0 0 1-6 0m0 0v6a3 3 0 0 1 0-6m0 0H6a3 3 0 0 1 6 0m0 6v7");
}

</style>
