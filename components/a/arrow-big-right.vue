<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3ws7egga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-right" /></template>
<style>
.o3ws7egga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12v-2a1 1 0 0 1 1-1h6a1 1 0 0 0 1-1V5c0-.369.631-.369 1 0l6 6a1.414 1.414 0 0 1 0 2l-6 6c-.369.369-1 .369-1 0v-3a1 1 0 0 0-1-1H5a1 1 0 0 1-1-1z");
}

</style>
