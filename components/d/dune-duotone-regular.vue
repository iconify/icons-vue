<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vx4tcy1ux"/><path class="akhe8vn1q"/><path class="x043no3hn"/><path class="s0kxqdbiw"/><path class="l8dn9jbyp"/><path class="olqfcgidt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dune-duotone-regular" /></template>
<style>
.akhe8vn1q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l8dn9jbyp {
  d: path("M2 15h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olqfcgidt {
  d: path("M6 19h12");
}

.s0kxqdbiw {
  d: path("M2 15a10 6 0 0 1 20 0");
}

.vx4tcy1ux {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 15a10 6 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x043no3hn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
