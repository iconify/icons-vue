<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pggrz7niw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filter-press" /></template>
<style>
.pggrz7niw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 4zA1.75 1.75 0 0 1 6 5.75v11.5A1.75 1.75 0 0 1 4.25 19a1.75 1.75 0 0 1-1.75-1.75V5.75A1.75 1.75 0 0 1 4.25 4m15.5 0za1.75 1.75 0 0 1 1.75 1.75v11.5A1.75 1.75 0 0 1 19.75 19A1.75 1.75 0 0 1 18 17.25V5.75A1.75 1.75 0 0 1 19.75 4M6 5.5h12M9 8.25V17m3-8.75V17m3-8.75V17");
}

</style>
