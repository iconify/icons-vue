<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aghs-4qzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-sad-sharp" /></template>
<style>
.aghs-4qzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16a8.944 8.944 0 1 1 4 4l-5 1Zm5-7h.01M15 9h.01M8 15a5.657 5.657 0 0 1 8 0");
}

</style>
