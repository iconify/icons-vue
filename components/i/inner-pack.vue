<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fheljtbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inner-pack" /></template>
<style>
.fheljtbol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 10h14.5A1.75 1.75 0 0 1 21 11.75v8a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 19.75v-8A1.75 1.75 0 0 1 4.75 10M3 10l-.5-4.5l4.5 1M21 10l.5-4.5l-4.5 1M8 10V4h8v6m-4-6v2.5m-9 7h18");
}

</style>
