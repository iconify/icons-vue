<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ez2td5bve"/><path class="ngahuxbaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dove" /></template>
<style>
.ez2td5bve {
  d: path("m17.75 12.25l-1.75-1c-.5-.75-1-1-2-1s-1.75.75-2.25 1.5C10.5 9 8 7 5 6c.75 2.75 1.75 4.75 3.25 6.25c-1.75.5-3.75.75-5.75.5l1.25 2c2 1 4 1.25 6 1.25C13 16 15 14.75 16 13Zm0 0C19.25 13.5 20 15.5 20 18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ngahuxbaa {
  d: path("M19.25 14c.5-1.25 1.5-1.75 2.5-1.5c-.25 1.25-1.25 1.75-2.5 1.5m.75 3c-1.25-.25-2.25.25-2.75 1.5c1.25.25 2.25-.25 2.75-1.5");
}

</style>
