<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-7mi-ili"/><path class="klhc1wvwx"/><path class="f33exibub"/><path class="sj9rw9tzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drift-duotone-thin" /></template>
<style>
.f-7mi-ili {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h9l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f33exibub {
  d: path("M3 12h9l6 -6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.klhc1wvwx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 12 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sj9rw9tzk {
  d: path("m12 12 6 6");
}

</style>
