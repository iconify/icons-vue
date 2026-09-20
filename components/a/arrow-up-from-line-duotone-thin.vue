<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rugctacrb"/><path class="e1cd9tzjc"/><path class="bztdq0bdr"/><path class="qdn88l2uv"/><path class="g4h6r4ykz"/><path class="h3z-uye4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-up-from-line-duotone-thin" /></template>
<style>
.bztdq0bdr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e1cd9tzjc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g4h6r4ykz {
  d: path("M12 4v12");
}

.h3z-uye4u {
  d: path("m8 8 4 -4 4 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qdn88l2uv {
  d: path("M7 20h10");
}

.rugctacrb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
