<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="h857n5bhq"/><path class="qrffjub9u"/><path class="t164-vbgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:confidence-threshold-outline-regular" /></template>
<style>
.e_6o-gbms {
  d: path("M6 10h13");
}

.h857n5bhq {
  d: path("M8 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.qrffjub9u {
  d: path("M12 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.r3faxubne {
  d: path("M4 4v16");
}

.t164-vbgd {
  d: path("M16 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
