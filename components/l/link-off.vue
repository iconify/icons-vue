<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb-4nob7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:link-off" /></template>
<style>
.sb-4nob7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17L7 17C4.2386 17 2 14.7614 2 12C2 9.2386 4.2386 7 7 7M15 7L17 7C19.7614 7 22 9.2386 22 12C22 13.2135 21.5677 14.326 20.8488 15.1919M17 17L15 17M8 12L12 12M2 2L22 22");
}

</style>
