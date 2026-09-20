<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="okud9xj_d"/><path class="brjpv3b7t"/><path class="raivi4yli"/><path class="m5hpqyobl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:layover-outline-regular" /></template>
<style>
.brjpv3b7t {
  d: path("M17.5 6.5V11");
}

.m5hpqyobl {
  d: path("M9.5 9.5h5l-5 5h5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okud9xj_d {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.raivi4yli {
  d: path("M17.5 13v4.5");
}

</style>
