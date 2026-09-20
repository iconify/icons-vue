<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zo132eb3n"/><path class="r40ntfh0k"/><path class="z786wkb6u"/><path class="zmjbj80iu"/><path class="xr4pgs06d"/><path class="kry_r4p8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flash-flood-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kry_r4p8f {
  d: path("m3 20 2.5 -2.5L8 20l2.5 -2.5L13 20l2.5 -2.5L18 20l2.5 -2.5");
}

.r40ntfh0k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 15 2.5 -2.5L8 15l2.5 -2.5L13 15l2.5 -2.5L18 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xr4pgs06d {
  d: path("m3 15 2.5 -2.5L8 15l2.5 -2.5L13 15l2.5 -2.5L18 15l2.5 -2.5");
}

.z786wkb6u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 20 2.5 -2.5L8 20l2.5 -2.5L13 20l2.5 -2.5L18 20l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zmjbj80iu {
  d: path("M13.5 4 11 6.5h2.5L11 9");
}

.zo132eb3n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 4 11 6.5h2.5L11 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
