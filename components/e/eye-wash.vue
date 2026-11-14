<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lyfe7ip9f"/><path class="hu0ig5b6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eye-wash" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hu0ig5b6b {
  d: path("M10 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2.5 6s-1.75 2.25-1.75 3.75a1.75 1.75 0 0 0 3.5 0C9.25 17.25 7.5 15 7.5 15m9 0s-1.75 2.25-1.75 3.75a1.75 1.75 0 0 0 3.5 0c0-1.5-1.75-3.75-1.75-3.75");
}

.lyfe7ip9f {
  d: path("M3.5 9c3-4.75 14-4.75 17 0c-3 4.75-14 4.75-17 0");
}

</style>
