<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k2jzr9u7f"/><path class="qnck32bfn"/><path class="gliukfoxr"/><path class="jjma1jbuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:colleague-outline-regular" /></template>
<style>
.gliukfoxr {
  d: path("M14 12v8h8v-8Z");
}

.jjma1jbuu {
  d: path("M16 12V9h4v3");
}

.k2jzr9u7f {
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qnck32bfn {
  d: path("M4 16a4 4 0 0 1 8 0");
}

</style>
