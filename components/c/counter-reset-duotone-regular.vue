<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="ojvfz8b9z"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="qrv8xdhwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:counter-reset-duotone-regular" /></template>
<style>
.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.ojvfz8b9z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 17 5 -5v5l5 -5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrv8xdhwx {
  d: path("m7 17 5 -5v5l5 -5v5");
}

.r3faxubne {
  d: path("M4 4v16");
}

</style>
