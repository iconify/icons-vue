<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lowe75bmn"/><path class="qory6h5iq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cardstock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lowe75bmn {
  d: path("M4 2.5h9.5l5 5v11H4Z");
}

.qory6h5iq {
  d: path("M4 18.5L6.5 21H21V10l-2.5-2.5m-5-5v5h5");
}

</style>
