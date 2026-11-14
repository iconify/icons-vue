<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ph23iqb9s"/><path class="ueo-8ccah"/><path class="p714u19_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:astrophysics" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p714u19_w {
  d: path("M12 9.5q.5 2 2.5 2.5q-2 .5-2.5 2.5q-.5-2-2.5-2.5q2-.5 2.5-2.5");
}

.ph23iqb9s {
  d: path("M4 4a11.31 4 45 0 0 16 16A11.31 4 45 0 0 4 4");
}

.ueo-8ccah {
  d: path("M20 4A11.31 4-45 0 0 4 20A11.31 4-45 0 0 20 4");
}

</style>
