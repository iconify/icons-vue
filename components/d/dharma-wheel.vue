<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><circle class="o_ly6ursf"/><path class="xl99tvxks"/><circle class="h_tsn8bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dharma-wheel" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_ly6ursf {
  cx: 12px;
  cy: 12px;
  r: 6.75px;
}

.xl99tvxks {
  d: path("M12 5.25v4m0 5.5v4M5.25 12h4m5.5 0h4M7.23 7.23l2.83 2.83m3.88 3.88l2.83 2.83m0-9.54l-2.83 2.83m-3.88 3.88l-2.83 2.83");
}

</style>
