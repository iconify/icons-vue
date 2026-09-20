<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mzsthfbrb"/><path class="y7cs2bcxe"/><path class="nzpsuduik"/><path class="ae-e09b3w"/><path class="j8_8pdbyc"/><path class="h7j2x7b-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:holiday-apartment-duotone-thin" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.h7j2x7b-d {
  d: path("M14 15h5v4h-5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8_8pdbyc {
  d: path("M12 3v9");
}

.mzsthfbrb {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nzpsuduik {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.y7cs2bcxe {
  fill: currentColor;
  d: path("M14 15h5v4h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
