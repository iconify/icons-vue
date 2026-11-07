<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha-908bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-share-round" /></template>
<style>
.ha-908bzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16a8.944 8.944 0 1 1 4 4l-5 1Zm4-1a3 3 0 0 1 3-3h5m-3-3l3 3l-3 3");
}

</style>
