<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="lpws5cv_a"/><path class="tbh515byk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gear-stick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpws5cv_a {
  cx: 12px;
  cy: 6.5px;
  r: 3.75px;
}

.tbh515byk {
  d: path("M10.75 5.25v2.5m2.5-2.5v2.5m-2.5-1.25h2.5M12 10.25v5.5m-5.12 4.57l1.49-3.64q.38-.93 1.38-.93h4.5q1 0 1.38.93l1.49 3.64q.38.93-.62.93h-9q-1 0-.62-.93");
}

</style>
