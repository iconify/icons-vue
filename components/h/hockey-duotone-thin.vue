<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crm2eebhm"/><path class="bq8hmj5od"/><path class="rmcfrrb-t"/><path class="bo88vlbuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hockey-duotone-thin" /></template>
<style>
.bo88vlbuz {
  d: path("M16 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.bq8hmj5od {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3v12c0 3 2 4 5 4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crm2eebhm {
  fill: currentColor;
  d: path("M16 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rmcfrrb-t {
  d: path("M6 3v12c0 3 2 4 5 4h6");
}

</style>
