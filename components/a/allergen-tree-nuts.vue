<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="p4_g-60gr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:allergen-tree-nuts" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.p4_g-60gr {
  d: path("M7.75 10.5C7.75 8.25 9.6 7 12 7s4.25 1.25 4.25 3.5Zm1 0V12c0 2.5 1.5 4.5 3.25 5.25c1.75-.75 3.25-2.75 3.25-5.25v-1.5M12 7l.5-1.25");
}

</style>
