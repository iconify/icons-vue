<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnbsnvidv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:friends-scheme" /></template>
<style>
.fnbsnvidv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M2 20.5c0-3.5 2.5-6 5.5-6c1.893 0 3.587.995 4.579 2.609m.913 3.052q.008.168.008.339m.75-13a3 3 0 1 0 6 0a3 3 0 1 0-6 0M18 21.25l-2.75-2.75A2 2 0 0 1 18 15.75a2 2 0 0 1 2.75 2.75Z");
}

</style>
