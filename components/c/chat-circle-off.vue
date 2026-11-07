<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1ky160nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-off" /></template>
<style>
.i1ky160nu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m18 19l-2 1a8.94 8.94 0 0 1-8 0l-5 1l1-5a8.94 8.94 0 0 1 0-8l1-2m5-3a9.22 9.22 0 0 1 11 11M2 2l20 20");
}

</style>
