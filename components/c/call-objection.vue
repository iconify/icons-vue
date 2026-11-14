<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngf2vh4bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-objection" /></template>
<style>
.ngf2vh4bl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5h2.5L8.75 6L7 7.25a8.5 8.5 0 0 0 4.25 4.25l1.25-1.75l3.5 1.5v2.25a2 2 0 0 1-2 2A12.5 12.5 0 0 1 2.5 4.75A2.25 2.25 0 0 1 4.75 2.5m15 11V18m0 3h.01");
}

</style>
