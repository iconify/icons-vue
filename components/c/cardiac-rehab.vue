<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_q6ow-sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cardiac-rehab" /></template>
<style>
.h_q6ow-sa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.468 16.561C14.229 18.638 12 20 12 20s-2.256-1.379-4.51-3.478M3.657 6.317A4.72 4.72 0 0 1 7.75 4C9.5 4 11.1 5 12 6.5C12.9 5 14.5 4 16.25 4c1.739 0 3.241.904 4.068 2.275M6.5 12h11m-13-3zA1.5 1.5 0 0 1 6 10.5v3A1.5 1.5 0 0 1 4.5 15A1.5 1.5 0 0 1 3 13.5v-3A1.5 1.5 0 0 1 4.5 9m15 0za1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-3A1.5 1.5 0 0 1 19.5 9");
}

</style>
