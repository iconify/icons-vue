<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ky4omnbla"/><path class="ib3hnj95a"/><path class="miofc3chu"/><path class="jusug-b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:interest-charged-outline-thin" /></template>
<style>
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

.jusug-b0m {
  d: path("M13.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.miofc3chu {
  d: path("m9 15 6 -6");
}

</style>
