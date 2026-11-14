<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9fqfgbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:group-shelter" /></template>
<style>
.n9fqfgbtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.883 6.232l4.316-2.726a1.5 1.5 0 0 1 1.602 0l4.316 2.726A1.5 1.5 0 0 1 16.316 9H7.684a1.5 1.5 0 0 1-.801-2.768M5.5 9v12m13-12v12m-10-5h7m-5.75 0v4.5m4.5-4.5v4.5");
}

</style>
