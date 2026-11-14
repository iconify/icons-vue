<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gvfoz9bkp"/><path class="lvyw4tbbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audiometer" /></template>
<style>
.gvfoz9bkp {
  d: path("M4.5 9.5a7.5 7 0 0 1 15 0");
}

.lvyw4tbbf {
  d: path("M2.5 9h4v6h-4Zm15 3.2V9h4v5.2M15 21.5v-3m3 3V15m3 6.5V17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
