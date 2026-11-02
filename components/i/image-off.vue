<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffe_0ctzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off" /></template>
<style>
.ffe_0ctzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 20c-.362.362-.448 1-1 1H5a2 2 0 0 1-2-2V5c0-.552.638-.638 1-1m5-1h10a2 2 0 0 1 2 2v10M3 17l7-7m5-2a1 1 0 1 0 2 0a1 1 0 0 0-2 0M2 2l20 20");
}

</style>
