<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d9acmebfe"/><path class="x6s5o0ble"/><path class="ulvbol07x"/><path class="uberx3r9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:image-variation-outline-thin" /></template>
<style>
.d9acmebfe {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uberx3r9c {
  d: path("M14 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ulvbol07x {
  d: path("M8 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.x6s5o0ble {
  d: path("m6 11 4 -4 3 3 4 -4");
}

</style>
