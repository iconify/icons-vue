<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="el753yuux"/><path class="a3ch5yb2h"/><path class="gj3ndm0la"/><path class="n8uuobb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-residency-outline-regular" /></template>
<style>
.a3ch5yb2h {
  d: path("M5 10h10");
}

.el753yuux {
  d: path("M4 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.gj3ndm0la {
  d: path("M15 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.n8uuobb1z {
  d: path("M18 18v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
