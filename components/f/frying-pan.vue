<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aonjvpbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:frying-pan" /></template>
<style>
.aonjvpbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 8c.75-.75-.75-1.75 0-2.5m4 2.5c.75-.75-.75-1.75 0-2.5m-8 5.25h12.5v2.5a3.5 3.5 0 0 1-3.5 3.5h-5.5a3.5 3.5 0 0 1-3.5-3.5ZM15.25 12h6");
}

</style>
