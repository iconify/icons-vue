<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xni26yb_w"/><path class="n6k59268i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grounding-pin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n6k59268i {
  d: path("M12 7q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25Q11.61 9.86 12 7");
}

.xni26yb_w {
  d: path("M12 21.25c-3.75-3.75-6.75-7-6.75-10.75a6.75 6.75 0 0 1 13.5 0c0 3.75-3 7-6.75 10.75");
}

</style>
