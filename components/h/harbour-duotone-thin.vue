<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="slwp6nw7r"/><path class="y41pjab_y"/><path class="alky4wu8l"/><path class="agduoheyh"/><path class="i64ili29r"/><path class="ylu4kimdh"/><path class="ig71m4b4e"/><path class="s0tzl36gy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:harbour-duotone-thin" /></template>
<style>
.agduoheyh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 13a7 7 0 0 1 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.alky4wu8l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i64ili29r {
  d: path("M10 4.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ig71m4b4e {
  d: path("M7 8.5h10");
}

.s0tzl36gy {
  d: path("M19 13a7 7 0 0 1 -14 0");
}

.slwp6nw7r {
  fill: currentColor;
  d: path("M10 4.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y41pjab_y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6.5V20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ylu4kimdh {
  d: path("M12 6.5V20");
}

</style>
