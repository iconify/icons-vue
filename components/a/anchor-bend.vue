<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="voo2v-e0j"/><path class="rlf9gvuii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anchor-bend" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rlf9gvuii {
  d: path("M11 4.5h5c2 0 2.5 2.5 4.5 2.5");
}

.voo2v-e0j {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2V21m-7.5-7a7.5 7.5 0 0 0 15 0M8 9.5h8");
}

</style>
