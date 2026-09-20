<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pgcaacbrb"/><path class="q--45jowd"/><path class="f33exibub"/><path class="sj9rw9tzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drift-duotone-bold" /></template>
<style>
.f33exibub {
  d: path("M3 12h9l6 -6");
}

.pgcaacbrb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h9l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q--45jowd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 12 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sj9rw9tzk {
  d: path("m12 12 6 6");
}

</style>
