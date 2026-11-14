<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zopneqb8e"/><path class="ct7v2db7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dapp-browser" /></template>
<style>
.ct7v2db7b {
  d: path("M8.75 11h6.5A1.75 1.75 0 0 1 17 12.75v3.5A1.75 1.75 0 0 1 15.25 18h-6.5A1.75 1.75 0 0 1 7 16.25v-3.5A1.75 1.75 0 0 1 8.75 11M12 11v7m-5-3.5h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zopneqb8e {
  d: path("M6.875 3h10.25A4.375 4.375 0 0 1 21.5 7.375v9.25A4.375 4.375 0 0 1 17.125 21H6.875A4.375 4.375 0 0 1 2.5 16.625v-9.25A4.375 4.375 0 0 1 6.875 3M2.5 8h19");
}

</style>
