<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="knhft4qdm"/><path class="s30vxrb5b"/><path class="pga6n1bci"/><path class="rjl8fe1sw"/><path class="qq9-4ficr"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:admission-control-duotone-regular" /></template>
<style>
.jkuojibnm {
  d: path("M3 20h18");
}

.knhft4qdm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pga6n1bci {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qq9-4ficr {
  d: path("m4 13 9 -9");
}

.rjl8fe1sw {
  d: path("M4 6v14");
}

.s30vxrb5b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 13 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
