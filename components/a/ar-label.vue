<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ljbue99-o"/><path class="yptcbs8tl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ar-label" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ljbue99-o {
  d: path("M7.125 2.5h9.75A2.625 2.625 0 0 1 19.5 5.125v1.75A2.625 2.625 0 0 1 16.875 9.5h-9.75A2.625 2.625 0 0 1 4.5 6.875v-1.75A2.625 2.625 0 0 1 7.125 2.5M12 9.5V13m.671.335l2.5 1.25A1.5 1.5 0 0 1 16 15.927v2.646a1.5 1.5 0 0 1-.829 1.342l-2.5 1.25a1.5 1.5 0 0 1-1.342 0l-2.5-1.25A1.5 1.5 0 0 1 8 18.573v-2.646a1.5 1.5 0 0 1 .829-1.342l2.5-1.25a1.5 1.5 0 0 1 1.342 0");
}

.yptcbs8tl {
  d: path("m8 15l4 2l4-2m-4 2v4.5");
}

</style>
