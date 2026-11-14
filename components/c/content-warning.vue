<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gn2obmb1s"/><path class="wz0wu-n0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:content-warning" /></template>
<style>
.gn2obmb1s {
  d: path("M12 2.75L21.75 20H2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wz0wu-n0g {
  d: path("M8 14.5c2-3.5 6-3.5 8 0c-2 3.5-6 3.5-8 0Zm4 0h.01");
}

</style>
