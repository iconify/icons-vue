<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t4yaetdui"/><path class="y4jee3bxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bone-crossed" /></template>
<style>
.t4yaetdui {
  d: path("M8.75 7L17 15.25a1.75 1.75 0 1 1 .25 2a1.75 1.75 0 1 1-2-.25L7 8.75a1.75 1.75 0 1 1-.25-2a1.75 1.75 0 1 1 2 .25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4jee3bxr {
  d: path("m15 10.75l2-2a1.75 1.75 0 1 0 .25-2a1.75 1.75 0 1 0-2 .25l-2 2M9 13.25l-2 2a1.75 1.75 0 1 0-.25 2a1.75 1.75 0 1 0 2-.25l2-2");
}

</style>
