<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm38hbotf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:filter-off" /></template>
<style>
.nm38hbotf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.6569 3L19.998 3C20.8858 3 21.3334 4.0707 20.7097 4.7025L15.5682 9.9113M14 14L14 18.4997C14 18.8146 13.8516 19.1112 13.5996 19.3L11.5996 20.7985C10.9403 21.2925 10 20.822 10 19.9982L10 15.6569M2 2L22 22");
}

</style>
