<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="d2s9n8aor"/><path class="esb5bcyio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:comet-tail" /></template>
<style>
.d2s9n8aor {
  cx: 7px;
  cy: 17px;
  r: 4.25px;
}

.esb5bcyio {
  d: path("M10.75 13.25c2.75-3.5 6-7.5 10.5-10.5m-9 14.5c3.25-1.5 6.25-4.25 8.75-8M6.75 11.5C8 8.25 10 5.25 13 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
