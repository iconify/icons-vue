<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r00g59dot"/><path class="ih_hzbmoj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inventory-count-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ih_hzbmoj {
  d: path("M4 20v-8h16v8Zm8 -8v8m-4 -8V4h8v8");
}

.r00g59dot {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20v-8h16v8Zm8 -8v8m-4 -8V4h8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
