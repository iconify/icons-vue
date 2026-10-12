<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kazaz2bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insurance-umbrella-sharp" /></template>
<style>
.kazaz2bqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 11.75a8.75 8.75 0 0 1 17.5 0a3.75 3.75 0 0 0-5.83 0a3.75 3.75 0 0 0-5.84 0a3.75 3.75 0 0 0-5.83 0Zm4.5 8.5v-3.5l.77-.64l2.71-2.22l.77-.64l.77.64l2.71 2.22l.77.64v4.5h-8.5z");
}

</style>
