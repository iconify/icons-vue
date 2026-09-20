<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z64snbciw"/><path class="z03i6130y"/><path class="zqix0ebqu"/><path class="cmt-chbtl"/><path class="iwanrcb5f"/><path class="s97tcsbyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:endurance-duotone-thin" /></template>
<style>
.cmt-chbtl {
  d: path("m2 20 6 -6 3 3 4 -4 7 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iwanrcb5f {
  d: path("M15 13V5");
}

.s97tcsbyl {
  d: path("M15 5h4v4h-4");
}

.z03i6130y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 13V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z64snbciw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 20 6 -6 3 3 4 -4 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zqix0ebqu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 5h4v4h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
