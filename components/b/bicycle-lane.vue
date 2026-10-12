<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rlgomkqfp"/><circle class="jagl1hbnl"/><path class="gr4kn5xwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bicycle-lane" /></template>
<style>
.gr4kn5xwx {
  d: path("M9 14.5h3L14.75 9l1.72 2.92M12 14.5L10.75 9M9.5 9H12m2.75 0l-.5-1.75h-1.5M2.75 21h18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jagl1hbnl {
  cx: 18px;
  cy: 14.5px;
  r: 3px;
}

.rlgomkqfp {
  cx: 6px;
  cy: 14.5px;
  r: 3px;
}

</style>
