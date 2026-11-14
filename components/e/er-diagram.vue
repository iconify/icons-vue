<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="is6iblb7y"/><path class="olhmju4wo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:er-diagram" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is6iblb7y {
  d: path("M5.125 3h2.25A2.625 2.625 0 0 1 10 5.625v.75A2.625 2.625 0 0 1 7.375 9h-2.25A2.625 2.625 0 0 1 2.5 6.375v-.75A2.625 2.625 0 0 1 5.125 3m11.5 0h2.25A2.625 2.625 0 0 1 21.5 5.625v.75A2.625 2.625 0 0 1 18.875 9h-2.25A2.625 2.625 0 0 1 14 6.375v-.75A2.625 2.625 0 0 1 16.625 3m-9.5 12h2.75a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 9.875 21h-2.75A2.625 2.625 0 0 1 4.5 18.375v-.75A2.625 2.625 0 0 1 7.125 15M10 6h4m3.75 3v9H12.5");
}

.olhmju4wo {
  d: path("m15.75 9l2 2.75l2-2.75");
}

</style>
