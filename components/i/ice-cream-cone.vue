<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmk29j5tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ice-cream-cone" /></template>
<style>
.kmk29j5tz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9.5a6 6 0 0 1 12 0ZM7.5 13h9q1 0 .45.83l-4.4 6.59q-.55.83-1.1 0l-4.4-6.59Q6.5 13 7.5 13");
}

</style>
