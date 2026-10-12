<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tmatvibqq"/><rect class="ukzl34ojd"/><path class="nn5-0kb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:checklist-board" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nn5-0kb5l {
  d: path("m6.25 11.5l1.25 1.25l2.25-2.25m-3.5 6l1.25 1.25l2.25-2.25M12 11.75h5.5m-5.5 5h5.5");
}

.tmatvibqq {
  d: path("M7.25 7.25L12 2.75l4.75 4.5");
}

.ukzl34ojd {
  width: 18.5px;
  height: 14px;
  x: 2.75px;
  y: 7.25px;
  rx: 2px;
}

</style>
