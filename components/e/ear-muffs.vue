<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp9r0-fke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ear-muffs" /></template>
<style>
.cp9r0-fke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 11v-1a7.25 7.25 0 0 1 14.5 0v1m-14.5 0zA2.25 2.25 0 0 1 7 13.25v3.5A2.25 2.25 0 0 1 4.75 19a2.25 2.25 0 0 1-2.25-2.25v-3.5A2.25 2.25 0 0 1 4.75 11m14.5 0za2.25 2.25 0 0 1 2.25 2.25v3.5A2.25 2.25 0 0 1 19.25 19A2.25 2.25 0 0 1 17 16.75v-3.5A2.25 2.25 0 0 1 19.25 11");
}

</style>
