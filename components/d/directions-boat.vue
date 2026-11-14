<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vz9hzre0n"/><path class="s821bor7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:directions-boat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s821bor7u {
  d: path("M6.5 12.5v-4H15l2 4m-8-4v-4h3v4");
}

.vz9hzre0n {
  d: path("M5.154 12.5h13.692a1.75 1.75 0 0 1 1.609 2.439l-1.5 3.5a1.75 1.75 0 0 1-1.609 1.061H6.654a1.75 1.75 0 0 1-1.609-1.061l-1.5-3.5A1.75 1.75 0 0 1 5.154 12.5");
}

</style>
