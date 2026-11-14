<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4slajbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-efficiency" /></template>
<style>
.b4slajbnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.682 5.542l-4.015 5.271A1.362 1.362 0 0 0 7.75 13h.92a1.5 1.5 0 0 1 1.471 1.794L9.75 16.75a.883.883 0 0 0 1.568.708l4.015-5.271A1.362 1.362 0 0 0 14.25 10h-.92a1.5 1.5 0 0 1-1.471-1.794l.391-1.956a.883.883 0 0 0-1.568-.708M14.75 18l2 2L21 15.75");
}

</style>
