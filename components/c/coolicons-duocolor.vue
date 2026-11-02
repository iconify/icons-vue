<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d60tyn8oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coolicons-duocolor" /></template>
<style>
.d60tyn8oc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.236 8.196C6.652 7.356 4 9.283 4 12a4 4 0 1 0 8 0a4 4 0 1 1 8 0c0 2.717-2.652 4.644-5.236 3.804");
}

</style>
