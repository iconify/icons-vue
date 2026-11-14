<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emfjgpb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dirty" /></template>
<style>
.emfjgpb7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.5c3 0 3.5 2 5.5 2c2.5 0 2.5 3 1 4.5c1.5 2 .5 5.5-2.5 5c-1.5 2-5 2-6 0c-3 .5-4.5-2.5-2.5-4.5c-2-2.5 0-5 2-4.5C8 5.5 9 4.5 10 4.5m8.25-.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-.75 14.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
