<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="msj--wien"/><path class="u9x3f9vnx"/><path class="g5tlcslpz"/><path class="c1nxh3m2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-right-down-duotone-thin" /></template>
<style>
.c1nxh3m2e {
  d: path("m9 15 5 5 5 -5");
}

.g5tlcslpz {
  d: path("M4 4h10v16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.msj--wien {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4h10v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u9x3f9vnx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 15 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
