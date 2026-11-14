<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y8lz6iynv"/><path class="iag6q0b6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:allergy-alert" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iag6q0b6w {
  d: path("M7.75 9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m1.75 7v5.5m9.824-5.018l1.5 2.812A1.5 1.5 0 0 1 19.5 21.5h-3a1.5 1.5 0 0 1-1.324-2.206l1.5-2.812a1.5 1.5 0 0 1 2.648 0M18 17.25v1M18 20h.01");
}

.y8lz6iynv {
  d: path("m10.529 4.334l.043.078a4.38 4.38 0 0 0 2.96 2.15l.088.018a1.179 1.179 0 0 1 .635 1.956l-.06.066a4.38 4.38 0 0 0-1.131 3.48l.011.088a1.179 1.179 0 0 1-1.665 1.209l-.081-.037a4.38 4.38 0 0 0-3.658 0l-.081.037a1.179 1.179 0 0 1-1.665-1.209l.011-.088a4.38 4.38 0 0 0-1.131-3.48l-.06-.066A1.179 1.179 0 0 1 5.38 6.58l.088-.018a4.38 4.38 0 0 0 2.96-2.15l.043-.078a1.179 1.179 0 0 1 2.058 0");
}

</style>
