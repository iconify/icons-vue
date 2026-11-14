<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l03-z0fpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breadcrumb-home" /></template>
<style>
.l03-z0fpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.141 10.359l2.312-2.312a2.19 2.19 0 0 1 3.094 0l2.312 2.312a2.2 2.2 0 0 1 .641 1.547v3.407A2.19 2.19 0 0 1 9.313 17.5H4.688A2.19 2.19 0 0 1 2.5 15.313v-3.407a2.2 2.2 0 0 1 .641-1.547M14.5 8.75L17.75 12l-3.25 3.25M21 12h.01");
}

</style>
