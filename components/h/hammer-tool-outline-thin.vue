<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w4onmpb6s"/><path class="zuwyzt6-u"/><path class="v8xtwkb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hammer-tool-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8xtwkb5y {
  d: path("M10 6c-2 1 -3 3 -3 4");
}

.w4onmpb6s {
  d: path("M10 6h7v4h-7Z");
}

.zuwyzt6-u {
  d: path("M13 10v12");
}

</style>
