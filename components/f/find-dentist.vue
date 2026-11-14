<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rr0clny2v"/><path class="tjdb2tbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:find-dentist" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rr0clny2v {
  d: path("M12 21.5c-4-4-7.5-8-7.5-12a7.5 7.5 0 0 1 15 0c0 4-3.5 8-7.5 12");
}

.tjdb2tbik {
  d: path("M10.75 6.75C9.5 6.75 9 7.75 9 9s.75 1.75 1 2.75l.5 1.5l1.5-2l1.5 2l.5-1.5c.25-1 1-1.5 1-2.75s-.5-2.25-1.75-2.25c-.75 0-.75.5-1.25.5s-.5-.5-1.25-.5");
}

</style>
