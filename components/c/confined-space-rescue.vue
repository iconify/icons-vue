<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fa8jygytk"/><path class="g8t4nebbt"/><path class="g_ixqwfmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:confined-space-rescue" /></template>
<style>
.fa8jygytk {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.g_ixqwfmx {
  d: path("M12 6.5v10a2 2 0 0 1-4 0v-1.25");
}

.g8t4nebbt {
  d: path("M2.5 21L12 6.5L21.5 21M12 6.5L16 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
