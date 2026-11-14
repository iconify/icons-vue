<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="ib24vybqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:community-points" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ib24vybqq {
  d: path("m12.625 8.625l.283.735a1.5 1.5 0 0 0 1.293.958l.799.057a.698.698 0 0 1 .392 1.236l-.612.501a1.5 1.5 0 0 0-.483 1.602l.203.661a.606.606 0 0 1-.915.682l-.753-.502a1.5 1.5 0 0 0-1.664 0l-.753.502a.606.606 0 0 1-.915-.682l.203-.661a1.5 1.5 0 0 0-.483-1.602l-.612-.501A.698.698 0 0 1 9 10.375l.799-.057a1.5 1.5 0 0 0 1.293-.958l.283-.735a.67.67 0 0 1 1.25 0");
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
