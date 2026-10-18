<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lakod4brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-up-line-sharp" /></template>
<style>
.lakod4brx {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 9L5 12C5 14.7614 7.2386 17 10 17C12.7614 17 15 14.7614 15 12L15 3.3753M19.2191 8.2739L15 3L10.6998 8.3753M21 21L3 21");
}

</style>
