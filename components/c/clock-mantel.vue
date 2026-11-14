<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vljkkricq"/><path class="aybbn9bmt"/><path class="uwf9jcb2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clock-mantel" /></template>
<style>
.aybbn9bmt {
  d: path("M8 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwf9jcb2y {
  d: path("M12 8.75V11l1.75 1");
}

.vljkkricq {
  d: path("M5 18v-8a7 7 0 0 1 14 0v8Zm-1.5 3h17m-13-3v3m9-3v3");
}

</style>
