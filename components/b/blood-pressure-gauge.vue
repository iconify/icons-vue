<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q4xfxibxn"/><path class="c14gu6hoo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blood-pressure-gauge" /></template>
<style>
.c14gu6hoo {
  d: path("M7.237 13.75a5.5 5.5 0 1 1 9.526 0M12 11l3-3m-3 3h.01M12 19.5v2.25");
}

.q4xfxibxn {
  d: path("M3.5 11a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
