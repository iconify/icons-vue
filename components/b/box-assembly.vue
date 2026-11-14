<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rrx4-qqxm"/><path class="bb6tw1f6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:box-assembly" /></template>
<style>
.bb6tw1f6b {
  d: path("m7.141 8.626l4.258-1.863a1.5 1.5 0 0 1 1.202 0l4.258 1.863a1.5 1.5 0 0 1 0 2.748l-4.258 1.863a1.5 1.5 0 0 1-1.202 0l-4.258-1.863a1.5 1.5 0 0 1 0-2.748M12 13.5v7M4 10L2.5 6.5l8-3.5L12 6.5m0 0L13.5 3l8 3.5L20 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rrx4-qqxm {
  d: path("M4 10v7l8 3.5l8-3.5v-7");
}

</style>
