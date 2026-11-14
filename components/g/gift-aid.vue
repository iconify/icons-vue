<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-6qlcctz"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-aid" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-6qlcctz {
  d: path("M4.75 7.5h14.5A1.75 1.75 0 0 1 21 9.25v1A1.75 1.75 0 0 1 19.25 12H4.75A1.75 1.75 0 0 1 3 10.25v-1A1.75 1.75 0 0 1 4.75 7.5M4.5 12v7.5q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T6 21h6.079M12 7.5v7.6m0-7.6c-2.5 0-4.5-1-4.5-2.5A1.5 1.5 0 0 1 9 3.5c1.5 0 3 2 3 4c0-2 1.5-4 3-4A1.5 1.5 0 0 1 16.5 5c0 1.5-2 2.5-4.5 2.5M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

</style>
