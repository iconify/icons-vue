<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_vo3wz-j"/><path class="eyzsrubqw"/><path class="p_-c85acz"/><path class="goi4-bbmu"/><path class="fozhwebbv"/><path class="tl_0od7zv"/><path class="ysxlqwpgz"/><path class="aaofdybgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:accessibility-test-duotone-thin" /></template>
<style>
.aaofdybgo {
  d: path("m9 18 3 -3 3 3");
}

.eyzsrubqw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10.5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fozhwebbv {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.goi4-bbmu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 18 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_-c85acz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 10.5V15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s_vo3wz-j {
  fill: currentColor;
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tl_0od7zv {
  d: path("M6 10.5h12");
}

.ysxlqwpgz {
  d: path("M12 10.5V15");
}

</style>
