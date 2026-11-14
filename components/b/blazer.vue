<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7ft-mcrc"/><path class="c7orrybfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blazer" /></template>
<style>
.c7orrybfo {
  d: path("m8 3l2 5.5l-1.5 1l3.5 3.25l3.5-3.25l-1.5-1L16 3m-4 12.5h.01M12 18.25h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7ft-mcrc {
  d: path("M8 3L3.5 5.5L2.5 21h19l-1-15.5L16 3");
}

</style>
