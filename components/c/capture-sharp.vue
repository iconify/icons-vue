<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8upawbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:capture-sharp" /></template>
<style>
.s8upawbqt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L22 4L22 20L2 20ZM6 11L6 8L10 8M14 8L18 8L18 11M18 13L18 16L14 16M10 16L6 16L6 13");
}

</style>
