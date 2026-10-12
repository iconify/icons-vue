<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><circle class="uadx0728c"/><circle class="xnt5zf0il"/><path class="o4z5kmbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:interest-rate" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o4z5kmbus {
  d: path("m15.5 8.5l-7 7");
}

.uadx0728c {
  cx: 9.25px;
  cy: 9.25px;
  r: 1.5px;
}

.xnt5zf0il {
  cx: 14.75px;
  cy: 14.75px;
  r: 1.5px;
}

</style>
