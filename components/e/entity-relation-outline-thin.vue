<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ztwbs-b3m"/><path class="bb7inz33j"/><path class="e_3sagvyd"/><path class="wjt99f33m"/><path class="l8l7-n69m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:entity-relation-outline-thin" /></template>
<style>
.bb7inz33j {
  d: path("M13.5 5a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
}

.e_3sagvyd {
  d: path("M13.5 16a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8l7-n69m {
  d: path("M11 12v5.5h2.5");
}

.wjt99f33m {
  d: path("M8.5 12H11V6.5h2.5");
}

.ztwbs-b3m {
  d: path("M2 9a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
