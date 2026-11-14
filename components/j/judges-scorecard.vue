<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f495tac8g"/><path class="bn7m5c4sx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:judges-scorecard" /></template>
<style>
.bn7m5c4sx {
  d: path("m12.625 6.375l.283.735a1.5 1.5 0 0 0 1.293.958l.799.057a.698.698 0 0 1 .392 1.236l-.612.501a1.5 1.5 0 0 0-.483 1.602l.203.661a.606.606 0 0 1-.915.682l-.753-.502a1.5 1.5 0 0 0-1.664 0l-.753.502a.606.606 0 0 1-.915-.682l.203-.661a1.5 1.5 0 0 0-.483-1.602l-.612-.501A.698.698 0 0 1 9 8.125l.799-.057a1.5 1.5 0 0 0 1.293-.958l.283-.735a.67.67 0 0 1 1.25 0");
}

.f495tac8g {
  d: path("M7.875 2h8.25A4.375 4.375 0 0 1 20.5 6.375v6.25A4.375 4.375 0 0 1 16.125 17h-8.25A4.375 4.375 0 0 1 3.5 12.625v-6.25A4.375 4.375 0 0 1 7.875 2M10.5 17v4.5h3V17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
