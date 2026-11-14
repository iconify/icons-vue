<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psnez77eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delta-v" /></template>
<style>
.psnez77eq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.661 17.124l3.205-8.361a1.75 1.75 0 0 1 3.268 0l3.205 8.361a1.75 1.75 0 0 1-1.634 2.376h-6.41a1.75 1.75 0 0 1-1.634-2.376M18.5 19.5v-15m-3.25 3.25L18.5 4.5l3.25 3.25");
}

</style>
