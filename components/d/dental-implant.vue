<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1frv6bze"/><path class="vt0v96eyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-implant" /></template>
<style>
.h1frv6bze {
  d: path("M6.5 8.5C5.5 5 7 3 9.5 3.25c1.25.15 1.75.75 2.5.75s1.25-.6 2.5-.75C17 3 18.5 5 17.5 8.5Zm-3.75 4q9.25-2.5 18.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vt0v96eyl {
  d: path("M11.057 11.25h1.886a1.75 1.75 0 0 1 1.728 2.03l-.933 5.75a1.75 1.75 0 0 1-1.727 1.47h-.022a1.75 1.75 0 0 1-1.727-1.47l-.933-5.75a1.75 1.75 0 0 1 1.728-2.03M8 14.5h8m-7 3h6");
}

</style>
