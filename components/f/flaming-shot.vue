<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr37-tjph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flaming-shot" /></template>
<style>
.cr37-tjph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 13l1 8h8l1-8Zm5-2.5c-2.5 0-3.5-2-2.5-4c.75 1 1.5.75 1.5-.5c0-1 .75-2 2-2.5c-.25 2 2.25 2.75 2 4.75c-.25 1.5-1.5 2.25-3 2.25M7.5 17h9");
}

</style>
