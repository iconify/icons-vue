<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wt_x2acmn"/><path class="a43ydrmjt"/><path class="ftaiyfqft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coming-soon-sign" /></template>
<style>
.a43ydrmjt {
  d: path("M8.75 8.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.ftaiyfqft {
  d: path("M12 7v1.75l1.5 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wt_x2acmn {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5V11a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 11V6.5A3.5 3.5 0 0 1 6 3m.5 11.5v7m11-7v7");
}

</style>
