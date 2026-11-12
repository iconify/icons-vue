<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktmwg97_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-angry" /></template>
<style>
.ktmwg97_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16a8.944 8.944 0 1 1 4 4l-5 1Zm4-7l2 1m6-1l-2 1m-6 5a5.657 5.657 0 0 1 8 0");
}

</style>
