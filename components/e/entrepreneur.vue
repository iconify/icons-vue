<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fxmq8_bbu"/><path class="s6fh-2b0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:entrepreneur" /></template>
<style>
.fxmq8_bbu {
  d: path("M14.472 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.931 0 1.814.108 2.625.311M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm14.682 7.818l-.177 3.005l-2.651 2.652l-2.829-2.829l2.652-2.651Z");
}

.s6fh-2b0e {
  d: path("m17.47 15.702l-2.122.353l-1.06 1.061l1.414.354m4.596 1.06l-.353 2.122l-1.061 1.06l-.354-1.414");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
