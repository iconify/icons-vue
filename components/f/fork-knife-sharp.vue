<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufv7wovhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fork-knife-sharp" /></template>
<style>
.ufv7wovhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75v4.5a2.75 2.75 0 0 0 5.5 0v-4.5M8 2.75v18.5m7.5-6.75h-1V7.75c0-2.75 1.5-5 3.75-5h.25V21h-3v-1.5Z");
}

</style>
