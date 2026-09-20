<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wyev84zxu"/><path class="h-yg3mbcx"/><path class="f33exibub"/><path class="sj9rw9tzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drift-duotone-regular" /></template>
<style>
.f33exibub {
  d: path("M3 12h9l6 -6");
}

.h-yg3mbcx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 12 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sj9rw9tzk {
  d: path("m12 12 6 6");
}

.wyev84zxu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h9l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
