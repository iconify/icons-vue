<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua1u3tbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:comet" /></template>
<style>
.ua1u3tbbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 17a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m6-2.5L20 4M4.5 14.5l7-7m-2 12l7-7");
}

</style>
