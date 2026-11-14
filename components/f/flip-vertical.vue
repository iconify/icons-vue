<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofxr8_-4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flip-vertical" /></template>
<style>
.ofxr8_-4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9H7.25A1.75 1.75 0 0 1 5.5 7.25V5.735a1.75 1.75 0 0 1 2.483-1.589l4.615 2.13A1.428 1.428 0 0 1 12 9m0 6H7.25a1.75 1.75 0 0 0-1.75 1.75v1.515a1.75 1.75 0 0 0 2.483 1.589l4.615-2.13A1.428 1.428 0 0 0 12 15m9-3H3");
}

</style>
