<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh-6tjixw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line-multi-round" /></template>
<style>
.uh-6tjixw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 10l4-4l4 3l6-6M3 4v12a4 4 0 0 0 4 4h14M7 16l4-3l4 2l6-5");
}

</style>
