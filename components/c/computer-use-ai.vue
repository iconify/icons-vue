<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uff-8ymft"/><path class="tatn1lhke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:computer-use-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tatn1lhke {
  d: path("M8.5 20.75h7m-3.5-5v5M10.05 6.48l5.4 2.29q.55.23 0 .48L13.8 10q-.55.25-.8.8l-.75 1.65q-.25.55-.46-.01L9.71 6.81q-.21-.56.34-.33");
}

.uff-8ymft {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 2.5px;
}

</style>
