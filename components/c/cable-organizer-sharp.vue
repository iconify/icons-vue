<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1phjkqis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cable-organizer-sharp" /></template>
<style>
.i1phjkqis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12.75V8C7.5 6 6 4.5 4 2.75m8 10v-10m4.5 10V8c0-2 1.5-3.5 3.5-5.25m-17.25 10h18.5v8.5H2.75zm4 4.25h10.5");
}

</style>
