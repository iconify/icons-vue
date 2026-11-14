<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxnwtcc1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earplugs-concert" /></template>
<style>
.gxnwtcc1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 12h7m-6 0V7.5a2.5 2.5 0 0 1 5 0V12m4.5 0h7m-6 0V7.5a2.5 2.5 0 0 1 5 0V12m-13 0v3c0 6 10.5 6 10.5 0v-3");
}

</style>
