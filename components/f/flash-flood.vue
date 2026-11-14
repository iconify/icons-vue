<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwcu_zryc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flash-flood" /></template>
<style>
.kwcu_zryc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5C7.5 19 8 12 13.5 12c3.5 0 5 3 3 5c-1-1.5-3.25-1.5-3.25 0M2.5 19.5h19M10.5 9h8a2 2 0 0 0 .25-4a4 4 0 0 0-7.25.25a2 2 0 0 0-1 3.75");
}

</style>
