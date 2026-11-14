<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v4o5x8b_s"/><path class="r39mbffqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hawaiian-shirt" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r39mbffqv {
  d: path("M12 12a1.75 1.75 0 1 1 2.5 2.5A1.75 1.75 0 1 1 12 17a1.75 1.75 0 1 1-2.5-2.5A1.75 1.75 0 1 1 12 12");
}

.v4o5x8b_s {
  d: path("M9 3L4.5 4.5l-2 6l3.5 1V21h12v-9.5l3.5-1l-2-6L15 3l-3 4.5Z");
}

</style>
