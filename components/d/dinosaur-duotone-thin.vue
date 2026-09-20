<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qeykcnbmx"/><path class="fspcj4gup"/><path class="oa6ed9-mr"/><path class="tbcegmb1y"/><path class="jnf_2db5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dinosaur-duotone-thin" /></template>
<style>
.fspcj4gup {
  d: path("M4 19c0 -4 3 -6 7 -6q1.5 -6 6 -6c0 -2 2 -3 3 -2s0 3 -1 3c0 3 -2 6 -5 7 0 2 -1 4 -3 4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.oa6ed9-mr {
  d: path("m4 19 -2 2");
}

.qeykcnbmx {
  fill: currentColor;
  d: path("M4 19c0 -4 3 -6 7 -6q1.5 -6 6 -6c0 -2 2 -3 3 -2s0 3 -1 3c0 3 -2 6 -5 7 0 2 -1 4 -3 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tbcegmb1y {
  d: path("M7 18v3");
}

</style>
