<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjekp7b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-smile-plus-sharp-fill" /></template>
<style>
.pjekp7b3n {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 11L22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2L13 2M9 9L9 12M15 9L15 12M8.7071 14.7071L9 15C10 16 11 16.5 12 16.5C13 16.5 14 16 15 15L15.2929 14.7071M19 1L19 9M15 5L23 5");
}

</style>
