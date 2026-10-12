<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="b7dof6bqe"/><circle class="b6b-3fpnt"/><path class="rb-m_ccyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cherry" /></template>
<style>
.b6b-3fpnt {
  cx: 17px;
  cy: 17.5px;
  r: 3.75px;
}

.b7dof6bqe {
  cx: 7px;
  cy: 17.5px;
  r: 3.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rb-m_ccyh {
  d: path("M7.25 13.75C8 9.5 10.75 6 14.5 4.5m2.25 9.25c-.5-3.5-1.25-6.5-2.25-9.25m0 0c1.5-2 4.5-2 6.5.5c-2 2-5 1.5-6.5-.5");
}

</style>
