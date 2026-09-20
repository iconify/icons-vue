<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jv2lmwb1w"/><path class="w9fsbztja"/><path class="b7uyqxwtl"/><path class="jqr98yvjb"/><path class="ky4omnbla"/><path class="ib3hnj95a"/><path class="miofc3chu"/><path class="jusug-b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:interest-charged-duotone-thin" /></template>
<style>
.b7uyqxwtl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ib3hnj95a {
  d: path("M8.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jqr98yvjb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 15 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jusug-b0m {
  d: path("M13.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jv2lmwb1w {
  fill: currentColor;
  d: path("M8.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.miofc3chu {
  d: path("m9 15 6 -6");
}

.w9fsbztja {
  fill: currentColor;
  d: path("M13.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
