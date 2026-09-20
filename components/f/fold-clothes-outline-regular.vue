<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k-9q2cbvs"/><path class="ju4i6gx3w"/><path class="dtjohzbue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fold-clothes-outline-regular" /></template>
<style>
.dtjohzbue {
  d: path("M5 17h14v3H5Z");
}

.ju4i6gx3w {
  d: path("M7 11h10v3H7Z");
}

.k-9q2cbvs {
  d: path("M5 5h14v3H5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
