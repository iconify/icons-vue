<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rkl060njf"/><path class="wl747ac6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:log-info" /></template>
<style>
.rkl060njf {
  d: path("M11.4 21.5H3.5v-19h14v7.7M7 7h7m-7 4h6.5M7 15h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wl747ac6w {
  d: path("M13 17.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm4.5-2h.01M17.5 18v1.75");
}

</style>
