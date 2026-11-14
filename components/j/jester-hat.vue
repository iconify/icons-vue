<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldla6jbfu"/><path class="pgc5pr5id"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jester-hat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldla6jbfu {
  d: path("M7.5 17.5c0-3.5-1-5.5-2.75-5.5C3.5 7.5 8 5.5 10 9.5c.5-2 1-3.25 2-4.25c1 1 1.5 2.25 2 4.25c2-4 6.5-2 5.25 2.5c-1.75 0-2.75 2-2.75 5.5m-8.25 0h7.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 15.75 21h-7.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

.pgc5pr5id {
  d: path("M2.25 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.25-9.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18.75 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
