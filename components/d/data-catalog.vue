<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jv539jb-z"/><path class="wecl8bbnr"/><path class="nynzlpb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-catalog" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jv539jb-z {
  d: path("M21.5 11.653V4.5C17 4 14 4.5 12 6c-2-1.5-5-2-9.5-1.5v14c4.462-.496 7.449-.008 9.449 1.462M12 6v9.1");
}

.nynzlpb7q {
  d: path("M14.75 15.25v5c0 .75 1.5 1.25 3.25 1.25s3.25-.5 3.25-1.25v-5");
}

.wecl8bbnr {
  d: path("M14.75 15.25a3.25 1.25 0 1 0 6.5 0a3.25 1.25 0 1 0-6.5 0");
}

</style>
