<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nheusxbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:constellation-orion" /></template>
<style>
.nheusxbxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.95 7.489l.648 2.723m.51 2.141l.139.583m-.224 1.95l-.379.705m8.548-7.253l-.269.647m-.06 2.053l.199.567m.726 2.076l.859 2.454M4.75 3.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m12 .5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-13 16.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m14-.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M7.5 14a1 1 0 1 0 2 0a1 1 0 1 0-2 0m3.5-2a1 1 0 1 0 2 0a1 1 0 1 0-2 0m3.5-2a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
