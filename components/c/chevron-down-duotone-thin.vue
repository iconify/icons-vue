<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xcc3n6bjz"/><path class="u54ztzb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-down-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u54ztzb9f {
  d: path("m5 9 7 7 7 -7");
}

.xcc3n6bjz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 9 7 7 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
