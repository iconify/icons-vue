<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wr3-l8bpk"/><path class="dylbr1d4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-kennel-run" /></template>
<style>
.dylbr1d4e {
  d: path("M9 21v-5a3 3 0 0 1 6 0v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wr3-l8bpk {
  d: path("M4 10.5L12 3l8 7.5V21H4Z");
}

</style>
