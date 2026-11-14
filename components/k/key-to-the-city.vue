<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xyfm4c6nv"/><path class="o3qt0wbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:key-to-the-city" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o3qt0wbrm {
  d: path("m8.875 6.5l.024.064a1.44 1.44 0 0 0 1.351.936h.024a.353.353 0 0 1 .226.625l-.048.04a1.5 1.5 0 0 0-.504 1.477l.069.308a.412.412 0 0 1-.642.425l-.003-.002a1.5 1.5 0 0 0-1.744 0l-.003.002a.412.412 0 0 1-.642-.425l.069-.308a1.5 1.5 0 0 0-.504-1.477l-.048-.04a.353.353 0 0 1 .226-.625h.024a1.44 1.44 0 0 0 1.351-.936l.024-.064a.401.401 0 0 1 .75 0");
}

.xyfm4c6nv {
  d: path("M2.5 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0m10.25 4.25L21 21m-5-5l2-2m1 5l2-2");
}

</style>
