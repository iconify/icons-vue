<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cm8lo6v1l"/><circle class="rs-d_y_0o"/><path class="mgse2ibxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:child-safety" /></template>
<style>
.cm8lo6v1l {
  d: path("m12 2.75l6.6 2.45a1 1 0 0 1 .65.94v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14a1 1 0 0 1 .65-.94Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mgse2ibxw {
  d: path("M9.5 16a2.5 2.5 0 0 1 5 0Z");
}

.rs-d_y_0o {
  cx: 12px;
  cy: 9px;
  r: 2px;
}

</style>
