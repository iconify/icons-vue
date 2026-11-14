<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ux1v5hmun"/><path class="ukk7z5bpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blasthole-drill" /></template>
<style>
.ukk7z5bpg {
  d: path("M8 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux1v5hmun {
  d: path("M2.5 2.5h4V18h-4Zm2 15.5v3.5m2-4.5v-4.5h8V9h4l3 3.5V17Z");
}

</style>
