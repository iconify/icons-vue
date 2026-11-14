<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0ukcw6za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dispatcher" /></template>
<style>
.q0ukcw6za {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9.75a7.25 7.25 0 0 1 14.5 0M3 9.75h3.5v4H3Zm14.5 3.9v-3.9H21v4h-.3m-15.95 0V16a3 3 0 0 0 3 3H11m8 3c-1.5-1.5-2.5-2.5-2.5-3.25a2.5 2.5 0 0 1 5 0c0 .75-1 1.75-2.5 3.25Z");
}

</style>
