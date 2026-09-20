<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="aepciub8g"/><path class="uycwhsbpb"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="jn24arf4i"/><path class="w8g3vrtdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:duplication-check-duotone-regular" /></template>
<style>
.aepciub8g {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.jn24arf4i {
  d: path("M8 10h6");
}

.ku_telleq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uycwhsbpb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w8g3vrtdm {
  d: path("M10 14h6");
}

.wywiukbgn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
