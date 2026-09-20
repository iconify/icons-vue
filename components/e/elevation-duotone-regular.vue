<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tfryo4bhy"/><path class="opio8j5fe"/><path class="wzcki-coh"/><path class="r3-bp3bbk"/><path class="f1um23b3l"/><path class="jor2cmbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:elevation-duotone-regular" /></template>
<style>
.f1um23b3l {
  d: path("M4 19h17");
}

.jor2cmbne {
  d: path("m6 16 4 -4 3 3 5 -5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.opio8j5fe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 19h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3-bp3bbk {
  d: path("M4 3v16");
}

.tfryo4bhy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wzcki-coh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 16 4 -4 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
