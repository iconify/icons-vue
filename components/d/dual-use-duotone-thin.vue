<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rrhhdyigh"/><path class="unyu66b5a"/><path class="k60u16b4z"/><path class="m7_k7qbff"/><path class="ip--tabyt"/><path class="twh8yufuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dual-use-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ip--tabyt {
  d: path("M6 3.5 3.5 6 6 8.5");
}

.k60u16b4z {
  d: path("M9 10v3");
}

.m7_k7qbff {
  d: path("M15 10v3");
}

.rrhhdyigh {
  fill: currentColor;
  d: path("M6 15a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.twh8yufuk {
  d: path("M18 3.5 20.5 6 18 8.5");
}

.unyu66b5a {
  d: path("M6 15a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

</style>
