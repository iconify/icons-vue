<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fjqm3kbck"/><path class="z0ljnmeyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:directions-run" /></template>
<style>
.fjqm3kbck {
  d: path("M13 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 4.5L10.5 14l3.5 2.5l-1.5 4.5m-2-7l-2 3.5l-4 .5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z0ljnmeyv {
  d: path("M6.5 11L9 8.5h4l2.5 3l3 .5");
}

</style>
