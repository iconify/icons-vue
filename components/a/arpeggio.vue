<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbnevvevy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arpeggio" /></template>
<style>
.mbnevvevy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3q2.5 2.25 0 4.5T7 12t0 4.5T7 21m5.25-16a2.75 1.75 0 1 0 5.5 0a2.75 1.75 0 1 0-5.5 0Zm0 7a2.75 1.75 0 1 0 5.5 0a2.75 1.75 0 1 0-5.5 0Zm0 7a2.75 1.75 0 1 0 5.5 0a2.75 1.75 0 1 0-5.5 0Z");
}

</style>
