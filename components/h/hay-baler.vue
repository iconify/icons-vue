<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m_oa4sbaz"/><path class="lhll1pu2b"/><circle class="r19_o2kzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hay-baler" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhll1pu2b {
  d: path("M8 10.5h9.75l3.5-3.5m-3.5 3.5v10.75m-6.5-10.75v10.75M14.5 10.5v10.75M8 16H5.75");
}

.m_oa4sbaz {
  d: path("m8.53 9.97l2.44-2.44Q11.5 7 12.25 7h8.25q.75 0 .75.75V17q0 .75-.53 1.28l-2.44 2.44q-.53.53-1.28.53H8.75q-.75 0-.75-.75v-9.25q0-.75.53-1.28");
}

.r19_o2kzq {
  cx: 4.25px;
  cy: 16px;
  r: 1.5px;
}

</style>
