<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lftfhufij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basket-return" /></template>
<style>
.lftfhufij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.099 12h9.802a2.625 2.625 0 0 1 2.59 3.057l-.625 3.75A2.625 2.625 0 0 1 16.276 21H7.724a2.625 2.625 0 0 1-2.59-2.193l-.625-3.75A2.625 2.625 0 0 1 7.099 12M7 6.5h10M9.5 4L7 6.5L9.5 9");
}

</style>
