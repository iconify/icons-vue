<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrk0z1wmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-up-right-round" /></template>
<style>
.mrk0z1wmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 13l4-4l-4-4m4 4H7a4 4 0 0 0-4 4v2a4 4 0 0 0 4 4h6");
}

</style>
