<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cj_gqbbkp"/><path class="ijyv-0p0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fair-ticket" /></template>
<style>
.cj_gqbbkp {
  d: path("M2.5 4.5h19V10a2 2 0 0 0 0 4v5.5h-19V14a2 2 0 0 0 0-4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijyv-0p0j {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M12 7.5v9M7.5 12h9");
}

</style>
