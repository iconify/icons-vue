<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-i_06bfu"/><circle class="zka8v6b8o"/><circle class="otw2wcc-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ambulance-check" /></template>
<style>
.f-i_06bfu {
  d: path("M2.75 5.75a1.5 1.5 0 0 1 1.5-1.5h10a1.5 1.5 0 0 1 1.5 1.5v2h1.9a1.5 1.5 0 0 1 1.25.67l2.1 3.03a1 1 0 0 1 .25.66V14a1 1 0 0 1-1 1h-16a1.5 1.5 0 0 1-1.5-1.5Zm13 2V15m-6.5-8.25v5.5M6.5 9.5H12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.otw2wcc-c {
  cx: 17px;
  cy: 19.5px;
  r: 1.5px;
}

.zka8v6b8o {
  cx: 7.25px;
  cy: 19.5px;
  r: 1.5px;
}

</style>
