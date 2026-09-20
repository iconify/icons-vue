<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zwfc0tbtb"/><path class="v0repaboa"/><path class="ys95wsbzg"/><path class="mhila7bcl"/><path class="jka0cfj-k"/><path class="hzsvawc8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-left-from-line-duotone-regular" /></template>
<style>
.hzsvawc8s {
  d: path("m8 8 -4 4 4 4");
}

.jka0cfj-k {
  d: path("M4 12h12");
}

.mhila7bcl {
  d: path("M20 7v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v0repaboa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys95wsbzg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwfc0tbtb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
