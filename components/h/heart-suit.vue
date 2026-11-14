<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wffwdccte"/><path class="jzcgyt6tl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-suit" /></template>
<style>
.jzcgyt6tl {
  d: path("M12 18.5L8.75 15A2 2 0 1 1 12 12.75A2 2 0 1 1 15.25 15ZM8.75 9L7.5 7.5a1 1 0 1 1 1.25-1.25A1 1 0 1 1 10 7.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wffwdccte {
  d: path("M4 2.5h16v19H4Z");
}

</style>
