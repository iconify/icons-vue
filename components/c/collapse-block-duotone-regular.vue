<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="wcpksnulb"/><path class="vthb-bcud"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="is4rzhsst"/><path class="tc-ybhuxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collapse-block-duotone-regular" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.is4rzhsst {
  d: path("m10 7 2 2 2 -2");
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

.tc-ybhuxl {
  d: path("m10 17 2 -2 2 2");
}

.vthb-bcud {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 17 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wcpksnulb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 7 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wywiukbgn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
