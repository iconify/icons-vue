<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jn_9u-bew"/><path class="pqqfnebfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loading-arm" /></template>
<style>
.jn_9u-bew {
  d: path("M3 21.5h9M6 7h3v14.5H6Z");
}

.pqqfnebfw {
  d: path("m7.5 7l6-3.5l5.5 8V15m-2 0h4l-1 4h-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
