<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbk6q8b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:afterburner" /></template>
<style>
.fbk6q8b-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.731 6.637l3.5 1A1.75 1.75 0 0 1 9.5 9.32v5.36a1.75 1.75 0 0 1-1.269 1.683l-3.5 1A1.75 1.75 0 0 1 2.5 15.68V8.32a1.75 1.75 0 0 1 2.231-1.683M16 8.5c2.5 0 4 2 5.5 3.5c-1.5 1.5-3 3.5-5.5 3.5a3.5 3.5 0 0 1 0-7M6 7v10");
}

</style>
