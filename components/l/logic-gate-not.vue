<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fty08tc3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:logic-gate-not" /></template>
<style>
.fty08tc3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.263 6.837l6.552 3.872a1.5 1.5 0 0 1 0 2.582l-6.552 3.872A1.5 1.5 0 0 1 5 15.871V8.129a1.5 1.5 0 0 1 2.263-1.292M16 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2.5 12H5");
}

</style>
