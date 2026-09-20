<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lh3gn3cks"/><path class="jisf7cbat"/><path class="sw8cph7mb"/><path class="fnbgpcbhf"/><path class="w-pek8c8r"/><path class="elc06ob4j"/><path class="l0v-b4kbr"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grounding-duotone-regular" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.elc06ob4j {
  d: path("M8 8h8");
}

.fnbgpcbhf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jisf7cbat {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.lh3gn3cks {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 2H5v15h14V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sw8cph7mb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w-pek8c8r {
  d: path("M14 2H5v15h14V7");
}

</style>
