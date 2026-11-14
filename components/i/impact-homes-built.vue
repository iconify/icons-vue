<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khyp-v9lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:impact-homes-built" /></template>
<style>
.khyp-v9lm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19v-7l2.25-3L7 12v7m2.75 0V8L12 5l2.25 3v11M17 19v-7l2.25-3l2.25 3v7m-19 0h19");
}

</style>
