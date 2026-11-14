<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uq___9v8s"/><path class="t55dmlbcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lamp-on" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t55dmlbcw {
  d: path("M12 14v7m-3.5 0h7M12 2v2.5m-6.5-.75L7 5m11.5-1.25L17 5");
}

.uq___9v8s {
  fill: currentColor;
  d: path("M8.91 7.5h6.18a1.75 1.75 0 0 1 1.612 1.068l1.269 3A1.75 1.75 0 0 1 16.359 14H7.641a1.75 1.75 0 0 1-1.612-2.432l1.269-3A1.75 1.75 0 0 1 8.91 7.5");
}

</style>
