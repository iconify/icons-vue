<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmtzamb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:binaural-audio" /></template>
<style>
.dmtzamb8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 13v-2a7.25 7.25 0 0 1 14.5 0v2m-14.5 0zA2.25 2.25 0 0 1 7 15.25v2.5A2.25 2.25 0 0 1 4.75 20a2.25 2.25 0 0 1-2.25-2.25v-2.5A2.25 2.25 0 0 1 4.75 13m14.5 0za2.25 2.25 0 0 1 2.25 2.25v2.5A2.25 2.25 0 0 1 19.25 20A2.25 2.25 0 0 1 17 17.75v-2.5A2.25 2.25 0 0 1 19.25 13m-9.75.5a5 5 0 0 1 0 6m5-6a5 5 0 0 0 0 6");
}

</style>
