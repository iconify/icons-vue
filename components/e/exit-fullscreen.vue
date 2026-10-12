<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u87xahb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:exit-fullscreen" /></template>
<style>
.u87xahb5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 3.75v3a2 2 0 0 1-2 2h-3m11.5 11.5v-3a2 2 0 0 1 2-2h3m0-6.5h-3a2 2 0 0 1-2-2v-3m-11.5 11.5h3a2 2 0 0 1 2 2v3");
}

</style>
