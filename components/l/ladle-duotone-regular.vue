<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rtc4d5stj"/><path class="zrx4-vn0g"/><path class="ovch9jidl"/><path class="mvm7r4bea"/><path class="jinvu3zma"/><path class="uac-t6brn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ladle-duotone-regular" /></template>
<style>
.jinvu3zma {
  d: path("M16 14a4 4 0 0 1 -8 0");
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ovch9jidl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 14c1 -5 -1 -10 -4 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rtc4d5stj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uac-t6brn {
  d: path("M16 14c1 -5 -1 -10 -4 -11");
}

.zrx4-vn0g {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 14a4 4 0 0 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
