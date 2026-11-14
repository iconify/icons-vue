<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9u-ywozo"/><path class="koso6ebyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-cycle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.koso6ebyl {
  d: path("M2.75 5.75h3v3M8.5 15.5c0-4.5 2.5-7 7-7c0 4.5-2.5 7-7 7m0 0l4-4");
}

.s9u-ywozo {
  d: path("M18.364 5.636a9 9 0 1 1-12.728 0");
}

</style>
