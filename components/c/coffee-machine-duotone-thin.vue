<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rg1-sjb4a"/><path class="ojcjn_j1b"/><path class="y93qarhow"/><path class="strt8mboj"/><path class="d8cg8bc8o"/><path class="qsb3g-bwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coffee-machine-duotone-thin" /></template>
<style>
.d8cg8bc8o {
  d: path("M12 13v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ojcjn_j1b {
  fill: currentColor;
  d: path("M8 16h8v3a4 4 0 0 1 -8 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qsb3g-bwo {
  d: path("M8 16h8v3a4 4 0 0 1 -8 0Z");
}

.rg1-sjb4a {
  fill: currentColor;
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.strt8mboj {
  d: path("M7 8h6");
}

.y93qarhow {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
