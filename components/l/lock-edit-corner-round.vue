<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpbjvmbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-edit-corner-round" /></template>
<style>
.rpbjvmbjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 21H8a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4h8a4 4 0 0 1 3.464 2M8 9V7a4 4 0 1 1 8 0v2m-2 12v-3l4-4l3 3l-4 4Z");
}

</style>
