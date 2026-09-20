<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aj1uncbqw"/><path class="y4-ssjnrw"/><path class="om9c7ck0x"/><path class="osdsz4bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:degree-fahrenheit-outline-regular" /></template>
<style>
.aj1uncbqw {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.om9c7ck0x {
  d: path("M13 8h7");
}

.osdsz4bam {
  d: path("M13 14h5");
}

.y4-ssjnrw {
  d: path("M13 8v12");
}

</style>
