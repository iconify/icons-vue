<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xb1xpachw"/><path class="gv5gocbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-2-line-duotone" /></template>
<style>
.gv5gocbpa {
  d: path("M19.5 12L9.5 12C7.83333 12 4.5 11 4.5 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xb1xpachw {
  stroke-linejoin: round;
  d: path("M14.5 17L19.5 12L14.5 7");
}

</style>
