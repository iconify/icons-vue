<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sntwqkbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-mechanic" /></template>
<style>
.sntwqkbah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 8h-12a4.5 4.5 0 0 1 9 0M7 8v1.5a4 4 0 0 0 8 0V8M3 21.25c0-2.75 3.5-4.75 8-4.75c1.267 0 2.454.158 3.506.447M19.5 14.25a2.25 2.25 0 1 0 2.25 2.25M18 18l-3 3");
}

</style>
