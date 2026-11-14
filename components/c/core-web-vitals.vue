<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fci96op4w"/><path class="yj-5h08in"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:core-web-vitals" /></template>
<style>
.fci96op4w {
  d: path("m12 20l-7.75-7.5C1.5 9.5 3.5 4 8 4c2 0 3.25 1.25 4 2.5c.75-1.25 2-2.5 4-2.5c4.5 0 6.5 5.5 3.75 8.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yj-5h08in {
  d: path("M4.25 12.5H8L10 9l3 7l2-3.5h4.75");
}

</style>
