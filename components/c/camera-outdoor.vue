<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="invd1db9g"/><path class="yobxcr_dx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-outdoor" /></template>
<style>
.invd1db9g {
  d: path("M19.5 5.5H8.75a3.75 3.75 0 0 0 0 7.5H19.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yobxcr_dx {
  d: path("M17.5 9.25a2 3.75 0 1 0 4 0a2 3.75 0 1 0-4 0ZM6 2.75h15.5M11.5 13v5.25h-6M2.5 15h3v6.5h-3Z");
}

</style>
