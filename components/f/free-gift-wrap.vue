<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zifh6m4tr"/><path class="okqytyb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:free-gift-wrap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.okqytyb5t {
  d: path("M12 6c0-3-3.5-3-3-1c.5 1.5 3 1 3 1");
}

.zifh6m4tr {
  d: path("M7 9.5h10a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 17v-4A3.5 3.5 0 0 1 7 9.5M4.25 6h15.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 7.75A1.75 1.75 0 0 1 4.25 6M12 6v14.5");
}

</style>
