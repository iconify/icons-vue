<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o0-9vw6lg"/><circle class="wijmr5spd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:book-reading" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o0-9vw6lg {
  d: path("M12 12.5Q9.75 11 6 11H3.75a1 1 0 0 0-1 1v6.5a1 1 0 0 0 1 1H6c2.5 0 4.5.4 6 1.25c1.5-.85 3.5-1.25 6-1.25h2.25a1 1 0 0 0 1-1V12a1 1 0 0 0-1-1H18q-3.75 0-6 1.5m0 0v8.25");
}

.wijmr5spd {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

</style>
