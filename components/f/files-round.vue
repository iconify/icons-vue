<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6qpa-o_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:files-round" /></template>
<style>
.r6qpa-o_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6H7a4 4 0 0 0-4 4v7a4 4 0 0 0 4 4h2a4 4 0 0 0 4-4v-6M8 6l5 5M8 6v4a1 1 0 0 0 1 1h4m-2-8h5m0 0l5 5m-5-5v4a1 1 0 0 0 1 1h4m0 0v6a4 4 0 0 1-4 4");
}

</style>
