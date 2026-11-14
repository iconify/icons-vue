<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qm_3ftbkj"/><path class="ukk5i1bfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-image" /></template>
<style>
.qm_3ftbkj {
  d: path("M3 3.5h18v17H3ZM3 14h18");
}

.ukk5i1bfk {
  d: path("m6 11l3-3l3 3m4-3.5h.01M6.5 17.25H12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
