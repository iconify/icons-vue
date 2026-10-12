<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="o9zalemks"/><path class="xvg8y8b2c"/><path class="fk_jg-8cw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-baby" /></template>
<style>
.fk_jg-8cw {
  d: path("M8.5 12.75c.75.75 2 .75 2.75 0m1.5 0c.75.75 2 .75 2.75 0m-4.75 4c.75.5 1.75.5 2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9zalemks {
  cx: 12px;
  cy: 13.5px;
  r: 6px;
}

.xvg8y8b2c {
  d: path("M4.25 17.5a8.75 8.75 0 1 1 15.5 0");
}

</style>
