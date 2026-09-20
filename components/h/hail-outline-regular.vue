<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c-pcdbceg"/><path class="s24u-_b8l"/><path class="je6wpwbmn"/><path class="t6z18wb5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hail-outline-regular" /></template>
<style>
.c-pcdbceg {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

.je6wpwbmn {
  d: path("M12 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s24u-_b8l {
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.t6z18wb5x {
  d: path("M10 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
