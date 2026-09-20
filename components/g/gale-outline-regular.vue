<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c5ipzfbmx"/><path class="d8abqfbpc"/><path class="fu2iodbya"/><path class="r_-onzaex"/><path class="gv9l4p83m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gale-outline-regular" /></template>
<style>
.c5ipzfbmx {
  d: path("M3 6h16");
}

.d8abqfbpc {
  d: path("M3 11h18");
}

.fu2iodbya {
  d: path("M3 16h16");
}

.gv9l4p83m {
  d: path("m21 19 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r_-onzaex {
  d: path("m16 19 -3 3");
}

</style>
