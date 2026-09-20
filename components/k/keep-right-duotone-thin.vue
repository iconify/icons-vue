<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mekga68ar"/><path class="kw_wimh-t"/><path class="o1qccsp0v"/><path class="bp3yu1oem"/><path class="d0n0p9bwt"/><path class="mz0o03tol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:keep-right-duotone-thin" /></template>
<style>
.bp3yu1oem {
  d: path("M12 22v-9l7 -7");
}

.d0n0p9bwt {
  d: path("M19 10.5V6h-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kw_wimh-t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 10.5V6h-4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mekga68ar {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 22v-9l7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mz0o03tol {
  d: path("M10 11 5 6");
}

.o1qccsp0v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 11 5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
