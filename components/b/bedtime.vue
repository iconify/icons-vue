<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h2wyzbbct"/><path class="f8wpp6b9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bedtime" /></template>
<style>
.f8wpp6b9a {
  d: path("M15.5 4.5H19l-3.5 4H19");
}

.h2wyzbbct {
  d: path("M12 3a6.5 6.5 0 0 0 9 9a9 9 0 1 1-9-9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
