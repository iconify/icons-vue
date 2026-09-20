<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o2bk0dgpo"/><path class="wx106lesi"/><path class="oqki-x-zf"/><path class="kbd2vhccj"/><path class="orxbg_b1j"/><path class="zuuudpbwi"/><path class="rdidnh2az"/><path class="isrkj8blm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dedupe-fuzzy-duotone-regular" /></template>
<style>
.isrkj8blm {
  d: path("M3 17h13");
}

.kbd2vhccj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o2bk0dgpo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oqki-x-zf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 11.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.orxbg_b1j {
  d: path("M3 4h13");
}

.rdidnh2az {
  d: path("m10 11.5 2 2 2 -2");
}

.wx106lesi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuuudpbwi {
  d: path("M3 8h14");
}

</style>
