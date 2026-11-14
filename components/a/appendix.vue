<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rnke8bc4z"/><path class="g_6tshbvk"/><path class="x29m_-b8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:appendix" /></template>
<style>
.g_6tshbvk {
  d: path("M3.5 5.5H17v16H3.5Z");
}

.rnke8bc4z {
  d: path("M8 2.5h9.5A2.5 2.5 0 0 1 20 5v13.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x29m_-b8m {
  d: path("M10.5 5.5v7l1.75-1.5L14 12.5v-7M6.5 17h7");
}

</style>
