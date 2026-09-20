<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t1sjjacis"/><path class="epoh96bbt"/><path class="u5a77nl7p"/><path class="x_46rtfdb"/><path class="l576i2b9k"/><path class="y7za30bps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-compare-outline-thin" /></template>
<style>
.epoh96bbt {
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l576i2b9k {
  d: path("M18 15.5V10h-5.5");
}

.t1sjjacis {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.u5a77nl7p {
  d: path("M6 8.5V14h5.5");
}

.x_46rtfdb {
  d: path("m9.5 12 2 2 -2 2");
}

.y7za30bps {
  d: path("m14.5 8 -2 2 2 2");
}

</style>
