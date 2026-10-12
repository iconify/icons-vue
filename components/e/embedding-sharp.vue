<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wpzo_lanh"/><path class="gyaiatuwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:embedding-sharp" /></template>
<style>
.gyaiatuwu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 7h.01m-.01 5h.01m-.01 5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wpzo_lanh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25h5.5v5.5h-5.5zm7.5 2.75h2.5m-1.5-1.5l1.5 1.5l-1.5 1.5m4-10.75h6v18.5h-6z");
}

</style>
