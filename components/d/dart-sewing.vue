<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aizxfybor"/><path class="esk2i4b8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dart-sewing" /></template>
<style>
.aizxfybor {
  d: path("M4 3.5h16V18c-2.5-2-5.5-2-8 0s-5.5 2-8 0Z");
}

.esk2i4b8a {
  d: path("m9.5 3.5l2.5 10l2.5-10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
