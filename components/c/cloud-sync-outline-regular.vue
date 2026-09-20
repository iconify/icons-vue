<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="is9m3gblc"/><path class="b1n727bkq"/><path class="fqpq4r8gf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cloud-sync-outline-regular" /></template>
<style>
.b1n727bkq {
  d: path("M13.5 15.5H16a1.5 1.5 0 0 1 1.5 1.5v2.5A1.5 1.5 0 0 1 16 21h-2.5");
}

.fqpq4r8gf {
  d: path("M10.5 21H8a1.5 1.5 0 0 1 -1.5 -1.5V17A1.5 1.5 0 0 1 8 15.5h2.5");
}

.is9m3gblc {
  d: path("M4 12.5A4 4 0 0 1 6 5a5 5 0 0 1 9.5 -1.5 5.5 5.5 0 0 1 4.5 9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
