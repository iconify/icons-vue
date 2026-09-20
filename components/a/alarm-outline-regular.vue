<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nqda50bqs"/><path class="wsg9rhonx"/><path class="md_wm9bov"/><path class="n7tvrlb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:alarm-outline-regular" /></template>
<style>
.md_wm9bov {
  d: path("m3 6 3 -3");
}

.n7tvrlb7x {
  d: path("m21 6 -3 -3");
}

.nqda50bqs {
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wsg9rhonx {
  d: path("M12 8v5h4");
}

</style>
